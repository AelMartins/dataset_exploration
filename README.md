# Aprendizagem de máquina

1. Acessamos a página [UC Irvine Machine Learning Repository](http://archive.ics.uci.edu) e escolhemos um dataset com a tarefa em **CLASSIFICAÇÃO** e uma quantidade acima de **1000 INSTÂNCIAS**.

2. Selecionei o dataset [Car Evaluation](http://archive.ics.uci.edu/dataset/19/car+evaluation).

3. Como estamos utilizando a aplicação [**WEKA**](https://waikato.github.io/weka-wiki/downloading_weka/), foi necessário encontrar o formato dos arquivos do dataset na extensão **.arff**. Para isso, através de uma rápida pesquisa no Google, encontrei o seguinte repositório com o exato arquivo que precisava: `https://github.com/renatopp/arff-datasets/blob/master/classification/car.arff`.

4. Após baixar todos o arquivo e o programa necessário, executei o Weka.
    - Acessei a opção `Explorer`.
    - Em `Preprocess` naveguei entre minhas pastas e abri o arquivo correspondente ao dataset `car.arff`.
    - Na aba `Classify` selecionei a opção `Choose` e escolhi o algoritimo **J48**.
    - As demais opções deichei como estavam e cliquei em `start`. A ideia deste processo é executar uma verificação da porcentagem de classificações corretas das instâncias. Para fins didáticos, é necessário que a quantidade de acertos esteja abaixo de 95%. Esse dataset específico atigiu um resultado proximo a 92%.


> [!NOTE]
> O arquivo .pdf [**ANALISE_WEKA_ALGORITMOS_DE_REGRA_E_DE_ARVORES**](./ANALISE_WEKA_ALGORITMOS_DE_REGRA_E_DE_ARVORES.pdf) é uma pesquisa comparativa entre os algoritmos que o programa WEKA disponibiliza utilizando o dataset mencionado anteriormente.
> O arquivo .pdf [**ANALISE_WEKA_MULTILAYER_PERCEPTRON**](./ANALISE_WEKA_MULTILAYER_PERCEPTRON.pdf) é uma pesquisa sobre um algoritmo específico no treinamento de aprendizagem de máquina que o programa WEKA disponibiliza utilizando o mesmo dataset mencionado.
