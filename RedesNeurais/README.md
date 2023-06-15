# Experimentos de redes neurais artificiais  🧠 💻 🧬

<p align="justify"> Olá computeiros! Vamos iniciar a nossa jornada para aprender mais sobre algoritmos genéticos? :ok_woman: </p>

<p align="justify"> Caso você tenha perdido a nossa introdução básica de redes neurais no README.md geral, sem problemas, vamos retornar a discussão por agora! :ok_woman: </p>

<h3 align="justify">  O QUE SÃO REDES NEURAIS? </h3>

<p align="justify">  Redes neurais são algoritmos que se baseiam em um processamento de dados similar ao processamento de informações de um cérebro humano que ocorrem por meio de um conjunto extremamente complexo de células, os neurônios, responsáveis pela tomada de decisão do raciocínio e corpo humanos. Os neurônios são formados por dendritos – conjuntos de terminais de entrada, pelo corpo central, e pelos axônios – terminais de saídas. </p>
<p align="justify">  A comunicação dos neurônios ocorrem por meia da sinapse – região onde dois neurônios entram em contato e transmitem impulsos nervosos. Estabelecido o funcionamento biológico, observa-se que o comportamento das redes neurais é similar ao de um neurônio visto que a estrutura computacional é baseada em um sistema três camadas, sendo um de input - valor de entrada; a camada escondida - neurônio soma os valores de entrada recebidos e incrementa um viés; e por fim, o output - valor de saída das operações. Na Figura 1, há a exemplificação estrutural de uma rede neural. </p>
 
<p align="justify"><img src="https://github.com/monocas/Redes-Neurais-e-Algoritmos-Geneticos/assets/106678040/4bfe07bf-4ac7-4d40-9bee-f07274d90472" width="500" height="300" > </p>
Figura 1. Estrutura de camadas das Redes Neurais.
<br> </br>

<p align="justify"> E o porque as redes neurais são tão admiradas e utilizas? Esse processamento de dados similar ao processamento de informações de um cérebro humano nos permitem realizar projetos de previsão e análise de dados seja predizendo seres temporais como as ações do mercado financeiro como também predizendo dados de saúde pública, ademais, as redes neurais também podem ter aplicações em sistemas de recomendação e também no desenvolvimento de IA's, quem não conhece o famoso Chat GPT? </p>

<p align="justify">  Existem inúmeros modos de categorização de redes conforme os dados fluem dos "nós" de entrada para os "nós de saída". Abordamos, neste repositório, os algoritmos de backpropagation.  </p>

<h4 align="justify"> BACKPROPAGATION </h4>

<p align="justify">  Este algoritmo é muito utilizado em redes neurais devido o ajuste do peso das conexões entre os neurônios com o objetivo de minimizar o erro entre as saídas da rede e os valores desejados. O processo em duas etapas: propagação para frente (forward propagation) e retropropagação do erro (backward propagation). </p>
  
<p align="justify">  O primeiro processo considerada os dados de entrada alimentados na rede e os valores de saída cálculados a partir da ativação dos neurNa etapa de propagação para frente, os dados de entrada são alimentados na rede, e as saídas são calculadas através das ativações dos neurônios, por sua vez, o segundo processo, determina que o erro entre as saídas da rede e os valores desejados é propagado de volta para a rede, ademais, os pesos das conexões são atualizados de forma a se obter um erro mínimo, utilizando o gradiente que é calculado através da derivada parcial do erro em relações aos pesos - alô Regra da Cadeia; e são repetidos até que a rede forneça uma saída com um erro aceitável.  </p>

<hr>

<h3 align="justify"> O QUE FAZEMOS NESTA SEÇÃO? </h3>

<p align="justify">  Nesta seção, iremos discorrer a respeito das atividades desenvolvidas e funções necessárias para os códigos, no total serão desenvolvidos sete experimentos que visam introduzir conceitos de genética em computação de modo a se utilizar das redes neurais. Todas as atividades foram desenvolvidas pelo Professor Daniel Cassar, docente da Ilum - School of Science. </p>

<p align="justify"> Existem dois tipos de arquivos nesta seção, os arquivos .ipynb definem os experimentos desenvolvidos, enquanto os do tipo .py se tratam de ferramentas auxiliadoras de código afim de otimiza-lo.</p>

<p align="justify"> Ok! Dada a introduzida básica, bora programar?</p>

<p align="justify"><img src="https://user-images.githubusercontent.com/106678040/225717363-f85c2c46-c3c2-4193-8d80-bdf15d48d438.gif" width="300" height="300" > </p>

## Arquivos .ipynb
<p align="justify">
:white_check_mark: <a href="https://github.com/monocas/Redes-Neurais-e-Algoritmos-Geneticos/blob/main/RedesNeurais/experimento%20R.01%20-%20derivadas.ipynb"> Experimento R.01 </a> - derivadas.ipynb - Neste arquivo, abordamos o problema do calculo da derivada de uma função qualquer de forma numérica usando a definição. </p>

<p align="justify">
:white_check_mark: <a href="https://github.com/monocas/Redes-Neurais-e-Algoritmos-Geneticos/blob/main/RedesNeurais/experimento%20R.02%20-%20classes.ipynb"> Experimento R.02 </a> - classes.ipynb - Nesta arquivo, aborda-se uma introdução a respeito de operações com classes. </p>
</p>

<p align="justify">
:white_check_mark: <a href="https://github.com/monocas/Redes-Neurais-e-Algoritmos-Geneticos/blob/main/RedesNeurais/experimento%20R.03%20-%20construindo%20um%20grafo%20automaticamente.ipynb"> Experimento R.03 </a> - construindo um grafo automaticamente.ipynb - Neste arquivo, abordamos a construção de grafos por meio de classes que geram automaticamente o grafo computacional. </p>

<p align="justify">
:white_check_mark: <a href="https://github.com/monocas/Redes-Neurais-e-Algoritmos-Geneticos/blob/main/RedesNeurais/experimento%20R.04%20-%20computando%20gradientes%20locais.ipynb"> Experimento R.04 </a> - construindo um grafo automaticamente.ipynb -  Neste notebook nós vamos atualizar a classe `Valor` para que ela seja capaz de computar o gradiente local de cada vértice numérico do grafo computacional. Esse cálculo será feito &ldquo;de trás para frente&rdquo;, iniciando pelo vértice folha e retornando até os vértices raiz. O nome desse processo é `backpropagation` e é o coração do processo de treinar uma rede neural artificial.
</p>

<p align="justify">
:white_check_mark: <a href="https://github.com/monocas/Redes-Neurais-e-Algoritmos-Geneticos/blob/main/RedesNeurais/experimento%20R.03%20-%20construindo%20um%20grafo%20automaticamente.ipynb"> Experimento R.05 </a> - construindo um grafo automaticamente.ipynb -  Neste arquivo, o objetivo é fazer com que a classe `Valor` seja capaz de realizar algumas operações necessárias para que seja usada na nossa rede neural artificial.
</p>

<p align="justify">
:white_check_mark: <a href="https://github.com/monocas/Redes-Neurais-e-Algoritmos-Geneticos/blob/main/RedesNeurais/experimento%20R.03%20-%20construindo%20um%20grafo%20automaticamente.ipynb"> Experimento R.06 </a> - redes neurais artificais.ipynb - Neste arquivo, iremos abordar a construção de uma rede neural por partes, primeiramente criando um neurônio artificial, depois uma camada de neurônios e, por fim, uma rede neural multicamadas.
. </p>

<p align="justify">
:white_check_mark: <a href="https://github.com/monocas/Redes-Neurais-e-Algoritmos-Geneticos/blob/main/RedesNeurais/experimento%20R.03%20-%20construindo%20um%20grafo%20automaticamente.ipynb"> Experimento R.07 </a> - treinando uma rede neural.ipynb - Neste arquivo, estamos no gran finale de redes neurais em que finalmente treinamos a nossa rede neural artificial tipo Multilayer Perceptron usando Python. </p>

<p align="justify">
:white_check_mark: <a href="https://github.com/monocas/Redes-Neurais-e-Algoritmos-Geneticos/blob/main/RedesNeurais/experimento%20R.03%20-%20construindo%20um%20grafo%20automaticamente.ipynb"> Experimento R.08 </a> - Treinando uma rede neural usando pytorch.ipynb - Neste arquivo, temos um spin off  do nosso gran finale sobre redes neurais, isto é, aprendemos a treinar uma rede neural artificial tipo Multilayer Perceptron usando `pytorch`.</p>


## Arquivos .py
<p align="justify">
:white_check_mark: <a href="https://github.com/monocas/Redes-Neurais-e-Algoritmos-Geneticos/blob/main/RedesNeurais/constantes.py">  constantes.py </a> - Neste arquivo estão alocadas todas as constantes utilizadas nos códigos fonte para a resolução dos exercícios. É um ambiente destinado para guardar e armazenar as constantes de modo a otimizar o código. </p>

<p align="justify">
:white_check_mark: <a href="https://github.com/monocas/Redes-Neurais-e-Algoritmos-Geneticos/blob/main/RedesNeurais/classes.py">  classes.py </a> - Neste arquivo estão alocados todas as classes criadas com o objetivo de auxiliar na otimização do código. </p>

<p align="justify">
:white_check_mark: <a href="https://github.com/monocas/Redes-Neurais-e-Algoritmos-Geneticos/blob/main/RedesNeurais/funcoes.py"> funcoes.py </a> - Neste arquivo estão alocadas todas as funções desenvolvidas e utilizadas nos códigos fonte para a resolução dos exercícios. É um ambiente destinado para as funções e suas implementações. </p>


