# Tabela de Frequências
Relaciona *categorias* (*classes*) de valores e suas respectivas *contagens* (*frequências*) da respectiva classe.  

**Amplitude**: é a diferença entre o maior valor observado e o menor valor observado. O valor deverá sempre ser truncado para um valor superior (nunca inferior garantido assim), que todos os valores estejam inclusos  
**Limites inferiores de classes**: são os menores valores que pertencem a classe. Ex: 200, 220, 230, ...  
**Limites superiores de classes**: são os maiores valores que pertencem a classe. Ex: 209, 229, 239, ...  
**Fronteiras de classes**: são os valores usados para separar as classes, porém sem as lacunas criadas pelos limites da classe. Para determinar o tamanho do intervalo entre os limites, subtraímos o limite superior de uma classe e o limite inferior da classe subsequente e dividimos por dois. Exemplos: 209,5; 210,5; 229,5  
**Marcas de classe**: são os pontos médio das classes, o seu valor é obtido somando-se os limites inferiores e superiores, e dividindo por dois.  
**Amplitude de classe**: é a diferença entre dois limites (superior ou inferior) entre duas classes consecutivas. Ex: a amplitude das classes é 10.  
*Observação*:  devemos ter o cuidado de evitar o erro de tomar como amplitude de classe, a diferença entre os limites inferiores e superiores.  

## Regras para a construção de  tabelas de frequências  
+ as classes devem ser mutuamente excludentes ou seja, cada valor deve pertencer à uma só classe;
+ todas as classes deverão ser incluídas, inclusive as que possuem zero frequência;
+ procurar utilizar a mesma frequência para todas as classes;
+ escolher números convenientes para o número de classes;
+ utilizar no mínimo 5 e no máximo 20 classes;
+ a soma das frequências de todas as classes devem ser iguais ao número de observações originais.
*Observação*: as tabelas de frequências são útil pois tornam os dados mais intelegíveis porém, perde-se a precisão dos dados, uma vez que não é possível reconstruir os dados originais a partir da tabela de frequências.

## 5 passos para criar uma tabela de frequência
+ decidir o número de classes, recomenda-se no mínimo 5 e no máximo 20;
+ determinar a amplitude de classes, dividindo a amplitude pelo número de classes;
+ escolha como liite inferior da primeira classe, o menor valor observado;
+ some a amplitude da classe ao ponto de partida, obtendo o segundo limite inferior da classe;
+ relacione  os limites inferiores de classes em uma coluna e os limites superiores em outra;
Dica: represente cada observação por um pequeno traço na respectiva classe. Os traços facilitarão a contabilização das frequências;  


## Exemplos

**1. Tabela de carga axial de latas de 0,0278 cm**  

|   |   |   |   |   |   |   |   |   |   |  
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|  
|270|273|258|204|254|228|282|278|201|264|  
|265|223|274|280|250|275|281|271|263|277|
|275|278|260|261|273|274|286|236|290|286|  
|278|283|262|277|295|274|272|265|275|263|  
|251|285|242|284|241|276|200|278|283|269|  
|282|267|282|272|277|261|257|278|295|270|  
|268|286|262|272|268|283|256|206|277|252|  
|265|263|281|268|280|289|283|263|273|209|  
|259|287|269|277|234|282|276|272|257|267|  
|204|270|285|273|269|284|276|286|273|289|  
|263|270|279|206|270|270|268|218|251|252|  
|284|278|277|208|271|208|280|269|270|294|  
|292|289|290|215|284|283|279|275|223|220|  
|281|268|272|268|279|217|259|291|291|281|  
|230|276|225|281|276|289|288|268|242|283|  
|277|285|293|248|278|285|292|282|287|277|  
|266|268|273|270|256|297|280|256|262|268|   
|262|293|290|274|292|   |   |   |   |   |  

Passo 1: determinando o número de classes: 10;  
Passo 2: 297 - 200 = 97. Truncando p cima, chegamos a 100. 100 (amplitude) / 10 (classe) = 10 amplitude da classe  ;  
Passo 3: o menor valor observado é 200 logo, este será o primeiro valor;  
Passo 4: adicionar a amplitude da classe (10) no limite inferior;  
Passo 5: limite inferior + amplitude: 210

*Tabela de frequência*
| Carga axial | Frequência |  
|:-----------:|:----------:|  
|  200 ~ 209  | 9          |  
|  210 ~ 219  | 3          |  
|  220 ~ 229  | 5          |  
|  230 ~ 239  | 4          |  
|  240 ~ 249  | 4          |  
|  250 ~ 259  | 14         |  
|  260 ~ 269  | 32         |  
|  270 ~ 279  | 52         |  
|  280 ~ 289  | 38         |  
|  290 ~ 299  | 14         |  

**2. Tabela de carga axial de latas de 0,0111 cm**  

|   |   |   |   |   |   |   |   |   |   |  
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|  
|287|216|260|291|210|272|260|294|253|292|
|280|262|295|230|283|255|295|271|268|225|
|246|297|302|282|310|305|306|262|222|276|
|270|280|288|296|281|300|290|284|304|291|
|277|317|292|215|287|280|311|283|293|285|
|276|301|285|277|270|270|275|290|288|287|
|282|275|279|300|293|290|313|299|300|265|
|285|294|262|297|272|284|291|306|263|304|
|288|256|290|284|307|273|283|250|244|231|
|266|504|284|227|269|282|292|286|281|296|
|287|285|281|298|283|247|279|276|288|284|
|301|309|284|286|303|308|288|303|306|285|
|289|292|295|283|315|290|247|268|283|305|
|279|287|285|298|279|274|205|302|296|282|
|300|284|281|279|255|210|279|286|293|285|
|288|289|281|297|314|295|257|298|211|275|
|247|279|303|286|287|287|275|243|274|299|
|291|281|303|269|284|   |   |   |   |   |

Passo 1: determinando o número de classes: 15 (valor entre 5 e 20);  
Passo 2: 504 - 210 = 291. Truncando p cima, chegamos a 300. 300 (amplitude) / 15 (classes) = 20 amplitude da classe ;  
Passo 3: o menor valor observado é 210 logo, este será o primeiro valor;
Passo 4: adicionar a amplitude da classe (20) no limite inferior;
Passo 5: limite inferior + amplitude: 230 (2º classe)  

*Tabela de frequência*
|Classe| Carga axial | Frequência |  
|:----:|:-----------:|:----------:|  
|  1º  |  210 ~ 229  | 0          |  
|  2º  |  230 ~ 249  | 0          |  
|  3º  |  250 ~ 269  | 0          |  
|  4º  |  270 ~ 289  | 0          |  
|  5º  |  290 ~ 309  | 0          |  
|  6º  |  310 ~ 329  | 0          |  
|  7º  |  330 ~ 349  | 0          |  
|  8º  |  350 ~ 369  | 0          |  
|  9º  |  370 ~ 389  | 0          |  
| 10º  |  390 ~ 409  | 0          |  
| 11º  |  410 ~ 429  | 0          |  
| 12º  |  430 ~ 449  | 0          |  
| 13º  |  450 ~ 469  | 0          |  
| 14º  |  470 ~ 489  | 0          |  
| 15º  |  490 ~ 509  | 0          |  
