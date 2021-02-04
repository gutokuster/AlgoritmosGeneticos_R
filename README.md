
# Inteligencia Artificial com Algoritmos Genéticos em R
**Jan/21**


#### Descrição
Se a evolução natural foi capaz de produzir seres vivos inteligentes e complexos, como nós humanos, porque não tentar simular este processo em um computador, para resolver problemas que, através de algoritmos tradicionais seriam muito difíceis?

  
:mortar_board: Curso Profº Fernando Amaral

#### Codificação   :mag_right:
Diz qual será a estrutura dos genes do cromossomo

- **Binária** >  O que se pode carregar em uma mochila?
- **Permutação** > Problema do caixeiro viajante.
- **Valores** > Equação matemática / Valores reais.

#### Pacote GA   :gift:
:small_orange_diamond: type: Informar o tipo de problema a ser resolvido. (Binário, Permutação ou Valor Real)
:small_orange_diamond: fitness: Qual será a função de adaptação 
:small_orange_diamond: min, max: Mínimo e máximo na busca, utilizado nas resoluções de permutação e valor real.   
:small_orange_diamond: nBbits: Número de bits, utilizados nas resoluções binárias.
:small_orange_diamond: popSize: Cromossomos, tamanho da população.
:small_orange_diamond: pcrossover: Probabilidade de permutação. (Default 0.8 / 8%)
:small_orange_diamond: pmutation: Probabilidade de mutação. (Default 0.1 / 1%)
:small_orange_diamond: maxiter: número máximo de iterações, quantidade de gerações. (Default 100)
:small_orange_diamond: elitism: Percentual de indivíduos mais adaptados que sobrevivem sem alterar a carga genética. (Default 0.5)
:small_orange_diamond: names: Nome das variáveis.
:small_orange_diamond: population: Definir população inicial.
:small_orange_diamond: crossover: Mudar o método de crossover.
:small_orange_diamond: mutation: Mudar o método de mutação.

#### Função de Adaptação
  
:small_orange_diamond: A função deve receber uma entrada(b,p,r) e retornar um valor real.
:small_orange_diamond: O GA deve buscar o maior valor real no retorno.
:small_orange_diamond: Para o maior valor de retorno, ele oferece a entrada como uma solução otimizada para o problema.
:small_orange_diamond: A função deve ter o mesmo comportamento para todos os tipos de problema (Binário, Permutação ou Valor Real)

  
#### Gráficos :bar_chart:
  
:small_orange_diamond: 

