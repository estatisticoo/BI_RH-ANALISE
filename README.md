# BI_RH-ANALISE

Total de Funcionários:
Utilizamos a função COUNTROWS(DatasetRH) para criar a medida representando o total de funcionários, oferecendo uma visão consolidada da equipe.

Distribuição de Gênero:

Total Feminino:
Aplicamos a função CALCULATE([Totalfuncionario], DatasetRH[Genero] = "Feminino") para mostrar o número de funcionárias em relação ao total, promovendo uma visão específica e detalhada.

Total Masculino:
Utilizamos a função CALCULATE([Totalfuncionario], DatasetRH[Genero] = "Masculino") para identificar o total de funcionários masculinos, permitindo uma análise comparativa com o total geral.

Percentual Masculino:
Empregamos a função DIVIDE([TotalMasculino],[Totalfuncionario],0) para calcular o percentual de funcionários masculinos em relação ao total, proporcionando uma compreensão rápida da distribuição de gênero na equipe.

Notas Importantes:

Os dados utilizados estão disponíveis no repositório, garantindo transparência e replicabilidade da análise.
Este relatório utiliza funções DAX eficazes no contexto de Recursos Humanos para fornecer insights valiosos.
Visualização Gráfica:

Gráfico de Barras Empilhadas:
Criamos um gráfico para visualizar a distribuição de gênero de maneira clara e comparativa.

Gráfico de Pizza:
Utilizamos a medida TotalFuncionario como valor e o dataset de disponibilidade para hora extra como legenda. Realizamos tratamento nos dados para substituir "S E N" por "Sim e Não", facilitando a compreensão do gestor.

Gráfico de Rosca - Índice de Envolvimento no Trabalho:
Implementamos um gráfico de rosca para analisar o total de funcionários em diferentes níveis de envolvimento no trabalho, oferecendo insights sobre a dedicação da equipe.

Essas visualizações visam proporcionar uma compreensão abrangente dos dados de Recursos Humanos, facilitando a tomada de decisões estratégicas.
