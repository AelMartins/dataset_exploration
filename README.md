# Aprendizagem de máquina

1. Acessamos a página `http://archive.ics.uci.edu` e escolhemos um dataset com a tarefa em **CLASSIFICAÇÃO** e uma quantidade acima de **1000 INSTANCIAS**.

2. Opitei pelo seguinte dataset: `http://archive.ics.uci.edu/dataset/19/car+evaluation`.

3. Utilizaremos a aplicação conhecida como [**WEKA**](https://weka.softonic.com.br/), foi necessário encontrar o formato dos arquivos do dataset com a extensão **.arff**. Para isso, com uma rápida pesquisa no Google, encontrei o seguinte repositório com exatamente o arquivo que precisava: `https://github.com/renatopp/arff-datasets/blob/master/classification/car.arff`.

4. Após baixar todos os arquivos e o programa necessário, executei o Weka.
    - Acessei a opção `Explorer`.
    - Em `Preprocess` naveguei entre meus arquivos e abri o arquivo correspondente ao dataset `car.arff`.
    - Na aba `Classify` selecionei a opção `Choose` e escolhi o algoritimo **J48**.
    - As demais opções deichei como estavam e cliquei em `start`. A ideia é executar uma verificação de classificação correta das instancias. Para fins didáticos, é necessário que a quantidade de acertos esteja a baixo de 95%. Esse dataset atigiu aproximadamente 92%