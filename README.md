


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
-  type: Informar o tipo de problema a ser resolvido. (Binário, Permutação ou Valor Real)
-  fitness: Qual será a função de adaptação 
-  min, max: Mínimo e máximo na busca, utilizado nas resoluções de permutação e valor real.  
*Obs: 'min, max' args is deprecated. Use 'lower, upper'*
-  nBbits: Número de bits, utilizados nas resoluções binárias.
-  popSize: Cromossomos, tamanho da população.
-  pcrossover: Probabilidade de permutação. (Default 0.8 / 8%)
-  pmutation: Probabilidade de mutação. (Default 0.1 / 1%)
-  maxiter: número máximo de iterações, quantidade de gerações. (Default 100)
-  elitism: Percentual de indivíduos mais adaptados que sobrevivem sem alterar a carga genética. (Default 0.5)
-  names: Nome das variáveis.
-  population: Definir população inicial.
-  crossover: Mudar o método de crossover.
-  mutation: Mudar o método de mutação.

#### Função de Adaptação
  
-  A função deve receber uma entrada(b,p,r) e retornar um valor real.
-  O GA deve buscar o maior valor real no retorno.
-  Para o maior valor de retorno, ele oferece a entrada como uma solução otimizada para o problema.
-  A função deve ter o mesmo comportamento para todos os tipos de problema (Binário, Permutação ou Valor Real).
