# BI_RH-ANALISE
Totalfuncionario:

Utilização da função COUNTROWS(DatasetRH) para criar a medida que representa o total de funcionários. Essa medida não é originária do dataset.
TotalFeminino:

Aplicação da função CALCULATE([Totalfuncionario], DatasetRH[Genero] = "Feminino") para criar a medida que representa o número de funcionários do sexo feminino em relação ao total de funcionários.
TotalMasculino:

Implementação da função CALCULATE([Totalfuncionario], DatasetRH[Genero] = "Masculino") para obter o total de funcionários masculinos em relação ao total de funcionários.
% Masculino:

Utilização da função DIVIDE([TotalMasculino],[Totalfuncionario],0) para calcular o percentual de funcionários masculinos em relação ao total. Essa medida foi criada para uma melhor visualização e interpretação dos dados.
Nota Importante:
O conjunto de dados utilizado para esta análise está disponível no próprio repositório, proporcionando a transparência e a replicabilidade da análise realizada. Este relatório visa oferecer insights valiosos por meio da aplicação eficaz de funções DAX no contexto de Recursos Humanos.

foi feita a criação de um grafico de barras empilhadas para facilitar a vizualização dos dados 

criação de um grafico de pizza utilizando a medida criada de Totaluncionario como valor e o dataset de disponivel para hora extra como legenda para obter um grafico percentual foi feito um tratamento dos dados para facilitar a vizualização por parte do gestor trocando os valores "S E N" ORIGINARIOS Do datset para "Sim e Não"

Criei um Grafico de rosca para analisar o total de funcionarios por indice de envolvimento no trabalho
  
