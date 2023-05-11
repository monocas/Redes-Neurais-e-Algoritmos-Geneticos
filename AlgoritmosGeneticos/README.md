# Experimentos de otimização e algoritmos genéticos :test_tube: :dna: :microscope: 

<p align="justify"> Olá computeiros! Vamos iniciar a nossa jornada para aprender mais sobre algoritmos genéticos? :ok_woman: </p>

<p align="justify"> Caso você tenha perdido a nossa introdução básica de algoritmos genéticos no README.md geral, sem problemas, vamos retornar a discussão por agora! :ok_woman: </p>

<h3 align="justify">  O QUE SÃO ALGORITMOS GENÉTICOS? </h3>

<p align="justify"> Os algoritmos genéticos podem ser compreendidos como algoritmos probabilísticos que convergem e solucionam problemas de grade complexa com mecanismos biológicos similares a concepções evolucionistas de Darwin, resolvendo, portanto, problemas de otimização e busca. Ele é composto por três operadores bem importantes: 
  <ul>
<li> Seleção; </li>
<li> Cruzamento;</li>
<li> Mutação</li>
</ul>

Esses operadores são responsáveis por selecionarmos os melhores individuos devido os processos de seleção natural que eliminam os individuos que não são válidos para o problema, por sua vez, o cruzamento dos individuos ocorre a fim de promover o surgimento de novas gerações e por fim, a mutação é necessária para a preservação da manutenção da diversidade genética da população, alterando arbitrariamente um ou mais componentes de uma estrutura escolhida.  </p>

<p align="justify">  Ressalta-se que a estrutura dos algoritmos é composta pela construção de uma população através da construção de individuos por meio dos seus genes. Essas populações são avaliadas por meio de uma função denominada de fitness (ou aptidão) que irá ser determinada através do cálculo da função objetivo, que depende das especificações de projeto. Geralmente, em problemas de otimização, busca-se encontrar soluções que minimizam ou maximizam o valor de aptidão. </p>

<p align="justify">  De modo geral, conclui-se que o algoritmo genético funciona por meio da aplicação de um conjunto de quatro operações operações: fitness, seleção, cruzamento e mutação. Após a geração aleatória dos membros da população, determina-se a sua aptidão e promove-se o processo de seleção, cruzamento e mutação, no final das operações, tem-se uma nova geração que espera-se apresentar uma melhor aproximação da solução do problema de otimização da população anterior. </p>


<hr>
<h3 align="justify"> O QUE FAZEMOS NESTA SEÇÃO? </h3>

<p align="justify">  Nesta seção, iremos discorrer a respeito das atividades desenvolvidas e funções necessárias para os códigos, no total serão desenvolvidos sete experimentos que visam introduzir conceitos de genética em computação de modo a se utilizar dos algoritmos genéticos. Todas as atividades foram desenvolvidas pelo Professor Daniel Cassar, docente da Ilum - School of Science. </p>

<p align="justify"> Existem dois tipos de arquivos nesta seção, os arquivos .ipynb definem os experimentos desenvolvidos, enquanto os do tipo .py se tratam de ferramentas auxiliadoras de código afim de otimiza-lo.</p>

<p align="justify"> Ok! Dada a introduzida básica, bora programar?</p>

<p align="justify"><img src="https://user-images.githubusercontent.com/106678040/225717363-f85c2c46-c3c2-4193-8d80-bdf15d48d438.gif" width="300" height="300" > </p>



## Arquivos .ipynb
<p align="justify">
:white_check_mark: <a href="https://github.com/monocas/Redes-Neurais-e-Algoritmos-Geneticos/blob/main/AlgoritmosGeneticos/experimento%20A.01%20-%20busca%20aleatoria.ipynb"> Experimento A.01 </a> - busca aleatoria.ipynb - Neste arquivo, abordamos o problema das caixas binárias, uma situação-problema em que temos um certo número de caixas e cada uma pode conter um valor do conjunto $\{0, 1\}$. O objetivo é encontrar uma combinação de caixas onde a soma dos valores contidos dentro delas é máximo para isso utiliza-se de algoritmos de busca aleatória. </p>

<p align="justify">
:white_check_mark: <a href="https://github.com/monocas/Redes-Neurais-e-Algoritmos-Geneticos/blob/main/AlgoritmosGeneticos/experimento%20A.02%20-%20busca%20em%20grade.ipynb"> Experimento A.02 </a> - busca em grade.ipynb - Nesta arquivo, também aborda-se o problema das caixas binárias, contudo, utiliza-se do algoritmo de busca em grade para a resolução desta situação-problema considerando 4 caixas. </p>
</p>

<p align="justify">
:white_check_mark: <a href="https://github.com/monocas/Redes-Neurais-e-Algoritmos-Geneticos/blob/main/AlgoritmosGeneticos/experimento%20A.03%20-%20algoritmo%20genetico.ipynb"> Experimento A.03 </a> - algoritmos genéticos.ipynb - Neste arquivo, também aborda-se o problema das caixas binárias, contudo, utiliza-se dos algoritmos genéticos para a resolução desta situação-problema considerando 4 caixas. Os algoritmos genéticos são ferramentas baseadas em conceitos de genética, responsáveis por otimização de códigos e solução de problemas complexos.  </p>

<p align="justify">
:white_check_mark: <a href="https://github.com/monocas/Redes-Neurais-e-Algoritmos-Geneticos/blob/main/AlgoritmosGeneticos/experimento%20A.04%20-%20caixas%20nao-binarias.ipynb"> Experimento A.04 </a>- caixas não binárias.ipynb - Neste arquivo, abordamos uma nova situação-problema: o problema das caixas não-binárias. Ele é similar aos conceitos vistos anteriormente e sua premissa é bem simples, temos um certo número de caixas e cada uma pode conter um número inteiro. O objetivo é encontrar uma combinação de caixas onde a soma dos valores contidos dentro delas é máximo.
</p>

<p align="justify">
:white_check_mark: <a href="https://github.com/monocas/Redes-Neurais-e-Algoritmos-Geneticos/blob/main/AlgoritmosGeneticos/experimento%20A.05%20-%20descobrindo%20a%20senha.ipynb"> Experimento A.05 </a> - descobrindo a senha.ipynb - Neste arquivo, aborda-se um novo problema: a função objetivo deve saber a senha correta e quantificar de alguma maneira o quão perto ou longe os palpites estão da solução (veja que isso é algo que não temos no mundo real. Nenhum site irá te dizer se você está acertando ou errando seu palpite). O critério de parada deste problema é quando a senha for descoberta.
</p>

<p align="justify">
:white_check_mark: <a href="https://github.com/monocas/Redes-Neurais-e-Algoritmos-Geneticos/blob/main/AlgoritmosGeneticos/experimento%20A.06%20-%20o%20caixeiro%20viajante.ipynb"> Experimento A.06  </a> - o caixeiro viajante.ipynb - Neste arquivo, aborda-se um novo problema: descobrir a rota de menor distância entre $n$ pontos no plano cartesiano (ou seja, $n$ pontos com coordenadas $(x,y)$). A rota pode se iniciar em qualquer um dos pontos disponíveis e deve terminar no ponto inicial, visitando todos os demais pontos apenas uma vez. Considere que a rota entre um ponto e outro é a linha reta que liga os dois pontos.

<p align="justify">
:white_check_mark: <a href="https://github.com/monocas/Redes-Neurais-e-Algoritmos-Geneticos/blob/main/AlgoritmosGeneticos/experimento%20A.07%20-%20aplicando%20restricoes.ipynb">  Experimento A.07  </a> - aplicando restricoes.ipynb - No problema da mochila você tem um número $n$ de itens disponíveis, cada um com um peso e um valor associado. Sua mochila tem a capacidade de carregar um número $p$ de quilogramas, sendo que mais que isso faz com que sua mochila rasgue e todos os itens dentro dela caiam no chão e se quebrem de maneira catastrófica (indesejado). Sua tarefa é encontrar um conjunto de itens (considerando os $n$ disponíveis) que maximize o valor contido dentro da mochila, porém que tenham um peso dentro da capacidade da mesma.
</p>

<p align="justify">
:white_check_mark: <a href="https://github.com/monocas/Redes-Neurais-e-Algoritmos-Geneticos/blob/main/AlgoritmosGeneticos/experimento%20GA.03%20-%20caixeiro%20com%20gasolina%20infinita.ipynb">  Experimento G.03 </a> - caixeiro viajante com gasolina infinita.ipynb - Neste arquivo, aborda-se um novo problema: descobrir a rota de maior distância entre $n$ pontos no plano cartesiano (ou seja, $n$ pontos com coordenadas $(x,y)$). A rota pode se iniciar em qualquer um dos pontos disponíveis e deve terminar no ponto inicial, visitando todos os demais pontos apenas uma vez. Considere que a rota entre um ponto e outro é a linha reta que liga os dois pontos. É um problema similar ao abordado no A.06, só que nesse caso, o nosso caixeiro não tem responsabilidade social, logo, temos que realizar a maximização do código. 


<p align="justify">
:white_check_mark: <a href="https://github.com/monocas/Redes-Neurais-e-Algoritmos-Geneticos/blob/main/AlgoritmosGeneticos/experimento%20GA.05%20-%20palindromos.ipynb
">  Experimento G.05 </a> - palindromos.ipynb - Neste experimento temos como objetivo encontrar pelo menos 10 palíndromos de 5 letras. Estes palíndromos devem ter pelo menos uma vogal. Não é necessário que eles formem palavras válidas em português ou qualquer outro idioma.
</p>


## Arquivos .py
<p align="justify">
:white_check_mark: <a href="https://github.com/monocas/Redes-Neurais-e-Algoritmos-Geneticos/blob/main/AlgoritmosGeneticos/constantes.py">  constantes.py </a> - Neste arquivo estão alocadas todas as constantes utilizadas nos códigos fonte para a resolução dos exercícios. É um ambiente destinado para guardar e armazenar as constantes de modo a otimizar o código. </p>

<p align="justify">
:white_check_mark: <a href="https://github.com/monocas/Redes-Neurais-e-Algoritmos-Geneticos/blob/main/AlgoritmosGeneticos/classes.py">  classes.py </a> - Neste arquivo estão alocados todas as classes criadas com o objetivo de auxiliar na otimização do código. </p>

<p align="justify">
:white_check_mark: <a href="https://github.com/monocas/Redes-Neurais-e-Algoritmos-Geneticos/blob/main/AlgoritmosGeneticos/funcoes.py"> funcoes.py </a> - Neste arquivo estão alocadas todas as funções desenvolvidas e utilizadas nos códigos fonte para a resolução dos exercícios. É um ambiente destinado para as funções e suas implementações. </p>
