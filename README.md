em python, crie um codigo para criar uma regra de cobrança através de uma base de agenda de normativos.
análise será divida em 2 categorias:
normas vigentes e não vigentes.


as colunas selecionaveis da base inicial para iniciar as duas saídas (vigente e não vigente) são:

Orgão Regulador
Tipo
Número
Data do Normativo
Ementa
Situação do documento
Data de início de vigência
Data de inclusão no MKCompliance
Segmentação
Aplicável a Instituição
Áreas afetadas
Diretorias Afetadas
Status da aplicação
Impacto
Status do Envio
Enviado por
Data de Envio
Prazo de Avaliação
Enviado para
Enviado para Área
Diretoria
Data de Resposta
Comentário
Escrito por
Escrito para
Área demandada
Diretoria demandada
Situação
Requer plano de ação
Gestor Responsavel
Plano de ação
Impacto Regulatório

essas são colunas existentes

crie e adicione as seguintes colunas não existentes (nome da coluna e formato):
QA - string
DataEntradaNorma - dd/mm/yyyy
StatusNorma - string
DataReferencia - dd/mm/yyyy

para essas colunas, deixa o espaço para que eu linke os dados que vao nela na tabela dentro do codigo para preenchimento.

abaixo as regras para cada saída separadamente:

regra saída de não vigente:

com todas as colunas acima, adiciona mais 24 colunas, sendo na sequencia de cobrança: 1-cobranca, 1-data-cobranca, 2-cobranca, 2-data-cobranca, 3-cobranca, 3-data-cobranca... até o 12. após o final, adicionas mais duas colunas, 'acima-12-cobrancas', 'ultima-data-cobranca'

regra saíde de vigente:

com todas as colunas acima, adiciona mais 6 colunas, sendo na sequencia de cobrança: 1-cobranca, 1-data-cobranca, 2-cobranca, 2-data-cobranca, 3-cobranca, 3-data-cobranca. após o final, adicionas mais duas colunas, 'acima-3-cobrancas', 'ultima-data-cobranca'

para os campos de data, no formato 'dd/mm/yyyy' e cobranca no formato de string.
