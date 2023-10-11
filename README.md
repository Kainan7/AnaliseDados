# AnaliseDados
Este código em Python realiza uma análise de cancelamentos de clientes com base em uma base de dados fornecida. O objetivo é identificar as principais causas de cancelamento e fornecer insights sobre como reduzir 
a taxa de cancelamento.

Passos:

Importar a Base de Dados: O código começa importando uma base de dados a partir de um arquivo CSV chamado "cancelamentos_sample.csv" usando a biblioteca pandas. Em seguida, ele remove a coluna "CustomerID" da tabela.
Visualizar a Base de Dados: Exibe a tabela de dados para que o usuário possa inspecionar as informações contidas nela.
Corrigir Valores Vazios: Remove as linhas da tabela que contêm valores vazios, garantindo que os dados estejam limpos e completos.
Análise Inicial dos Cancelamentos: Calcula a porcentagem de clientes que cancelaram seus contratos e fornece insights sobre a duração do contrato dos clientes. Além disso, realiza uma análise agrupada para calcular a média de várias métricas.
Análise das Causas do Cancelamento: Cria gráficos com a biblioteca plotly.express para visualizar a relação entre variáveis como idade, dias de atraso, ligações para o call center e o cancelamento dos clientes. 
Com base nesses gráficos, o código toma a decisão de filtrar a tabela para remover clientes com alta dias de atraso e chamadas para o call center, a fim de reduzir a taxa de cancelamento.

Resultado:
Após a análise e as correções, a taxa de cancelamento foi reduzida para 18%, e as principais causas de cancelamento identificadas incluem a forma de contrato mensal, necessidade de ligações para o call center e 
atraso no pagamento. O código pode ser usado como base para análises semelhantes em outros conjuntos de dados para otimizar a retenção de clientes.
