------------------------------------------------------------------------------------------------
<h1>Se��o 01 - Qual � o tipo do seu dado?</h1>

Empresas vendem produtos diferentes, o que voc� vende mais o que voc� vende menos, e predizer quando vender� mais e como vender� mais.
Usar estat�stica e aplicar ela no dia a dia.

Antes de come�ar com Estat�stica � entender o tipo de dado que estamos lidando naquele momento.

Dados Categ�ricos
	Sexo: Masculino, Feminino, ou at� mesmo N�o declarar - Dado do tipo Categ�rico.
	N�o � poss�vel comparar
	
Dado Ordinal (Existe uma ordem)
	Nota: 1, 2, 3, 4.., 10
	N�o � poss�vel saber a diferen�a de um intervalo e outro

Dados Intervalar
	Graus Celsius: 25�C, 30�C, etc
	Diferen�a � mensur�vel, � precisa

Dados Racional

Os tr�s tipos importantes: Categ�ricos, Ordinal e Intervalar.

Exemplo:
Nome do Aluno	Aulas Assistidas
Mauricio	2
Natalia		4
Felipe		4
Jo�o		6
Jos�		5

Histograma
	- Gr�fico que tenta mostrar a quantidade de frequ�ncias e quantas vezes elas repetem
	- Quantidade de aulas assistidas
	- Frequencia que as coisas acontecem na distribui��o
	
Curva Normal
	- Distribui��o em gr�fico comum
	- Muita gente na m�dia e pouca gente que est� nas extremidades
	- � importante conhecer a curva para saber qual teste estat�stico ser� o melhor teste
	- Entretanto, antes de tudo � necess�rio saber os tipos de dados
	- Depois pensar no formato da distribui��o

Gr�fico da curva normal do exemplo
<img src="1.png">
<img src="2.png">


A ideia deste curso � ensinar Estat�stica Aplicada, ou seja, queremos que voc� saia daqui sabendo muito mais do que � M�dia, Mediana ou Correla��o, e quando usar cada uma dessas coisas. Temos certeza que voc� j� ouviu aquela frase: "Existem mentiras, grandes mentiras e estat�stica". E isso n�o � t�o mentira, porque se voc� n�o souber escolher o teste certo que voc� vai aplicar, a fun��o de m�dia correta que voc� vai usar, voc� vai chegar em n�meros que n�o explicam nada sobre o conjunto de dados que voc� tem.

E estat�stica hoje � fundamental. N�s temos um monte de informa��es, sejam elas na pol�tica, na economia, nos esportes ou mesmo na sua empresa. A sua empresa vende hoje para um monte de pessoas um monte de produtos diferentes; voc� pode extrair informa��es de l�. A estat�stica vai te ajudar a entender um pouco mais sobre os seus dados: o que voc� vende mais, o que voc� vende menos, vai te ajudar at� a predizer que produto vai vender mais e quando vai vender mais.

Mas, obviamente, voc� vai ter que entender estat�stica a fundo. Aqui n�o ficaremos entrando naquele matematiqu�s de como cada teste estat�stico funciona. �bvio que haver� um pouco de matem�tica porque n�o tem como fugir disso, mas este curso n�o � para matem�ticos, � um curso para quem quer usar estat�stica e aplic�-la no dia-a-dia.

A primeira coisa que temos que entender sobre estat�stica � entender sobre n�meros, sobre os tipos de dados que estamos usando naquele momento. Imagine um formul�rio que voc� responde na rua sobre seu sexo:

Sexo:

Masculino
Feminino
N�o quero declarar
Este � um tipo de dado que chamamos de Categ�rico, pois temos categorias e um � diferente do outro e n�o possuem rela��o. Masculino n�o � melhor que Feminino e assim por diante.

Um outro tipo de dado comum � o que chamamos de dado Ordinal. Por exemplo, voc� acabou de fazer um curso e pedem para voc� avaliar o professor de 1 a 10:

Nota: ( )1 ( )2 ( )3 ( )4 ( )5 ( )6 ( )7 ( )8 ( )9 ( )10
Esse tipo de dado chamamos de Ordinal porque existe uma ordem: 1 < 2 < 3 <...< 10, mas n�o conseguimos comparar a diferen�a do 1 para o 2. Existe o sentimento que de 1 para 2 � a mesma coisa que de 2 para 3, por�m n�o conseguimos medir de maneira precisa. Esse intervalos podem variar de pessoa para pessoa. � diferente medir, por exemplo, uma temperatura: ao medir a temperatura de um ser humano e indicar 36 oC, saberemos que � preciso. De 36 para 37 a diferen�a � de exatamente um grau Celsius.

A temperatura, ent�o, � um exemplo de dado Intervalar:

25C -- 25,2C -- 26C
A diferen�a de um para o outro � mensur�vel e precisa.

Outro tipo de dado, menos comum, � o Racional. Ele � bem parecido com o Intervalar: ele � composto de n�meros em ordem e podemos medir a diferen�a de um para o outro. Por�m, nesse tipo de dado o 0 (zero) significa a aus�ncia daquela coisa. Medindo a temperatura em Celsius, 0 oC significa que est� frio, mas n�o a aus�ncia de temperatura. Em graus Kelvin, 0 K significa a aus�ncia de temperatura. Nos estudos em F�sica, faz sentido lidar com os dados Racionais, por�m aqui em Estat�stica trabalharemos com os tr�s primeiros tipos de dados: Categ�rico, Ordinal e Intervalar.

Saber isso � necess�rio porque dependendo do seu tipo de dado, voc� tem que escolher o m�todo estat�stico certo. Na pr�xima aula veremos se a M�dia Aritm�tica que aprendemos na escola faz sentido para qualquer tipo de dado. Conhecer o seu tipo de dado � fundamental.

Com isso claro, vamos continuar. Raramente em Estat�stica iremos analisar apenas um n�mero. N�s a utilizamos porque temos um monte de dados e precisamos reduzi-los a um n�mero que os traduza e que possamos entend�-los de maneira f�cil.

Vamos come�ar, ent�o, a agrupar dados.

Exemplo:
Temos os nomes dos alunos de uma escola e a quantidade de aulas que cada um assistiu:

Maur�cio: 2 aulas

Nat�lia: 4 aulas

Felipe: 4 aulas

Jo�o: 6 aulas

Jos�: 5 aulas

Agora queremos entender essas informa��es: quantas aulas os alunos assistem na escola? Para tal, utilizaremos um Histograma. O Histograma � um gr�fico que mostra a quantidade de frequ�ncias e quantas vezes elas se repetem.

Quantidade de aulas assistidas	Quantidade de alunos
2	1
4	2
5	1
6	1
Perceba que temos a mesma informa��o s� que disposta de outra maneira.

Por�m, com essa tabela, conseguimos criar um gr�fico:

histograma

Esse � o Histograma, o gr�fico que mostra a frequ�ncia em que as coisas aconteceram em minha distribui��o. Nesse exemplo utilizamos poucos dados, mas imaginemos uma distribui��o maior. Deixaria bem claro o que est� acontecendo, em rela��o �s aulas assistidas, na escola.

Se tra�armos uma linha por esse gr�fico:

histograma-linha

Essa curva formada � important�ssima e � o que chamamos de Curva Normal. � essa curva que esperamos numa distribui��o comum. Se, por exemplo, desenharmos o Histograma da altura de um homem brasileiro, veremos que poucos estar�o nas faixas menores e maiores e muitos nas faixas centrais. Muita gente estar� na m�dia e pouca nos dois extremos. Entender se sua distribui��o est� dentro ou n�o dessa curva tamb�m � de extrema import�ncia para escolhermos o teste estat�stico ideal. Falaremos mais para frente sobre ela.

Revendo:
antes de estudarmos a M�dia, ou o Teste de Correla��o, ou Teste de Hip�tese (veremos tudo isso nas pr�ximas aulas), devemos entender os tipos de dados: Categ�ricos, Ordinais e Intervalares.
Depois pensamos no formato da distribui��o. Uma maneira f�cil � desenhando um Histograma, que nos mostra a frequ�ncia da distribui��o. Os testes a serem aplicados mudam se ela for Normal ou n�o.
Com essas informa��es na cabe�a, voc� est� pronto para come�ar a entender mais sobre estat�stica.

<h2>Tipo de Dado</h2>
Um professor entrega para os alunos um formul�rio para que eles avaliem o curso. Os alunos podem escolher um n�mero de 1 a 5.
Qual o tipo de dado aqui?
R: Ordinal, temos uma ordem, mas n�o conseguimos medir precisamente a diferen�a de um para outro.

Temos uma lista de alturas, em cent�metros, das pessoas de uma universidade.
Qual o tipo de dado aqui?
R: Intervalar. A diferen�a entre um e outro � precisa, mas n�o existe aus�ncia de altura.

Um cientista tem a lista da temperatura di�ria no Deserto do Saara, em Kelvin.
Esse exemplo representa qual tipo de dado:
R: Racional. Kelvin � uma medida especial, pois "0" (zero) significa aus�ncia de temperatura.

Uma locadora de filmes tem a lista de tipos de filme que cada usu�rio gosta. Jo�o gosta de "romance", enquanto Maria gosta de "a��o".
Qual tipo de dado?
R: Categ�rico. Afinal, s�o categorias.

O que � um histograma?
R: Gr�fico de barras que mostra a frequ�ncia de cada valor num conjunto de dados


---------------------------------------------------------------------------------------------------------------
<h1>Se��o 02 - Primeiros passos com R</h1>

Na aula passada n�s come�amos nosso curso de Estat�stica com os tipos de dados. Agora vamos come�ar a colocar isso em pr�tica. Esta aula servir� basicamente para introduzir a ferramenta R. R � uma linguagem de programa��o muito utilizada por estat�sticos, ent�o � uma linguagem em que voc� tem um monte de comandos com tudo que precisamos de estat�stica j� pronto. Muitas pessoas gostam de utilizar o Microsoft Excel, que � uma boa ferramenta, mas aqui vamos falar de coisas mais avan�adas, onde o suporte do Excel deixa a desejar. R � a ferramenta que com certeza � usada por pessoas de Estat�sticas.

Instala��o
� uma instala��o padr�o como a de qualquer software que voc� faz em sua m�quina. Ele � gratuito, basta baixar da internet. Ent�o, por exemplo, para o sistema operacional Mac [ou Windows], buscamos no Google "R para MacOS". A pesquisa retorna a p�gina do R para o MacOS. Baixe a vers�o certa para o seu sistema e fa�a a instala��o. Ap�s seguir os passos de instala��o, voc� est� pronto para utiliz�-lo.

Nas nossas aulas utilizaremos direto a linha de comando, pois ela � independente do sistema operacional. Se preferir, voc� pode baixar a vers�o com a interface gr�fica.

Ao digitarmos �R� logo na primeira linha:

Alura:~ alura$ R
O programa retorna diversas informa��es relacionadas ao R, como a vers�o instalada e algumas dicas:

R version 3.1.2 (2014-10-31) -- "Pumpkin Helmet"
Copyright (C) 2014 The R Foundation for Statistical Computing
Platform: x86_64-w64-mingw32/x64 (64-bit)

R � um software livre e vem sem GARANTIA ALGUMA.
Voc� pode redistribu�-lo sob certas circunst�ncias.
Digite 'license()' ou 'licence()' para detalhes de distribui��o.

R � um projeto colaborativo com muitos contribuidores.
Digite 'contributors()' para obter mais informa��es e
'citation()' para saber como citar o R ou pacotes do R em publica��es.

Digite 'demo()' para demonstra��es, 'help()' para o sistema on-line de ajuda,
ou 'help.start()' para abrir o sistema de ajuda em HTML no seu navegador.
Digite 'q()' para sair do R.
O R interpreta tudo que escrevermos: se digitarmos �1�, retornar� �1�, se digitarmos �1+1�, retornar� �2�. Ou seja, qualquer express�o matem�tica retornar� seu resultado:

>  1

[1] 1

> 1+1

[1] 2

> 3*8+2/5

[1] 24.4

> (3*7)/4

[1] 5.25
Podemos tamb�m utilizar par�nteses para definir preced�ncia de opera��es e outros operadores que j� estamos acostumados.

Vari�veis
Podemos querer guardar resultados de opera��es para utilizarmos depois. Para tal, utilizamos o s�mbolo �<-�, que tem formato de seta, ap�s o nome que queremos dar � essa vari�vel (por exemplo �numero�):

> numero <- (3*7)/4
Depois disso, toda vez que digitar �numero� e der ENTER, o programa retornar� o resultado da conta atribu�da a essa vari�vel:

> numero
[1] 5.25
Podemos fazer contas com ela:

> numero * 2
[1] 10.5
Listas
Um outro comando muito importante para se guardar informa��es � o m�todo �c( )�, que guardar� uma lista de n�meros. Funciona da mesma forma como guardamos uma vari�vel:

> lista <- c(1, 2, 3, 4, 5, 6)
Se digitarmos �lista�:

> lista
[1] 1 2 3 4 5 6
Igualmente, podemos fazer opera��es com uma lista:

> lista * 2
[1] 2 4 6 8 10 12
Conjunto de Dados e Histograma
Agora vamos utilizar o m�todo de criar listas para montarmos histogramas. Vamos usar o exemplo da aula passada, onde t�nhamos os dados de quantas aulas cada aluno assistiu na escola:

> aulas <- c(2, 4, 4, 6, 6, 6, 6, 8, 8, 10)
Com esta lista de dados guardada podemos plotar um histograma de forma muito simples:

> hist(aulas)
No mesmo instante abrir� uma janela com o histograma desenhado:



Temos a op��o de customizar esse histograma por meio de comandos que encontramos digitando �?hist�. Para voltar �s linhas de comando basta digitar �q�.

Como voc� deve ter percebido, o R vem com seu pr�prio manual. D� uma lida nele para ir se acostumando com os comandos, uma vez que todas essas fun��es d�o suporte a muita coisa. Outra op��o � procurar na internet esse manual ou partes dele. Tente digitar �hist R� no Google.

Revendo
Nesta aula aprendemos:

Como instalar o R.
Como fazer uma opera��o b�sica em R
Como usar uma vari�vel com um nome qualquer utilizando <-
Listas utilizando o m�todo c( )
Como criar um histograma utilizando o comando hist()

<h2>Opera��es b�sicas</h2>

Qual o resultado da opera��o (1+2)*3/2 no R?
R: 4.5


<h2>Criar listas</h2>
Como se cria uma lista com os n�meros 1, 2, 3 no R?
R: c(1,2,3)
Fun��o c()

<h2>Desenhar Histograma</h2>
Como se desenha um histograma no R?
R: hist(numero)
Fun��o hist() recebe a lista de n�meros e desenha o histograma

<h2>Documenta��o</h2>
Como ler a documenta��o da fun��o hist()?
R: ?hist

--------------------------------------------------------------------------------------------------
<h1>Se��o 03 - M�dia, Mediana e Moda</h1>

M�dia
x1+x2+x3..+xn/n
	
	- Ser� que essa m�dia aritm�tica � vi�vel?
	- Talvez seja e talvez n�o, depende do tipo de dado.
	- Que tipo informa��o o dado �?
	- Pois, dependendo do tipo de dado, como ir� trat�-lo sera diferente

Outliers / Fora da Curva
	- A m�dia aritm�tica � completamente sens�vel a outliers, pois um valor muito grande pode afetar

Mediana - Mediana � o elemento que est� localizado no meio da distribui��o, quando ela est� ordenada
	- Pega a distribui��o
	- Ordenar em ordem crescente
	- Mediana � o elemento que est� localizado no meio da distribui��o, quando ela est� ordenada
	- Escolher dois n�meros que est�o no meio e fazer a m�dia aritmim�tica para quantidade de n�meros pares.
	- Mediana sofre menos com outliers
	- Ordeno a distribui��o e pego a do meio

Se n�o tiver outliers, a m�dia aritim�tica � uma boa solu��o
Se o tipo de dado � ordinal, a m�dia � uma escolha ruim, a mais vi�vel � a mediana.

Moda - Elemento que mais se repete na distribui��o

N�meros Ordinais - Mediana ou Moda
Objetivo: Encontrar tend�ncia central

M�dia Aritm�tica
A primeira coisa que iremos mostrar � a M�dia Aritm�tica. Muito provavelmente voc� j� deve ter estudado esse assunto na escola. Se pedirmos para voc� calcular a M�dia, por exemplo, de 1, 2, 3 e 4, voc� far�:

(1 + 2 + 3 + 4)/4 = 10/4 = 2,5

De modo geral:

(x1 + x2 + x3 + ... + xn)/n

Agora fa�amos uma pergunta: ser� mesmo que para todo conjunto de n�meros devemos utilizar a M�dia Aritm�tica para encontrarmos uma Tend�ncia Central? Talvez. Devemos saber que tipo de dado possu�mos. Lembra-se da primeira aula de Estat�stica? A M�dia serve para dados Ordinais, ou Intervalares? Vejamos um exemplo:

Imagine que voc� � um professor e no final da aula voc� entregue um formul�rio para os alunos preencherem com a nota que eles te dariam, de 1 a 10:

Nota: ( )1 ( )2 ( )3 ( )4 ( )5 ( )6 ( )7 ( )8 ( )9 ( )10  [dado do tipo Ordinal]
Segue que: 1� aluno: 10 2� aluno: 1 3� aluno: 1 4� aluno: 1

Fazendo a M�dia:

(10 + 1 + 1 + 1)/4 = 3,25
N�o � estranho? O 10 dado pelo primeiro aluno n�o parece exce��o? Voc� �, claramente, um professor nota 1! Perceba que escolher a M�dia Aritm�tica, sem pensar no tipo de dado, pode te levar para uma informa��o estranha.

Veja outro exemplo que pode nos enganar:

Em uma empresa os sal�rios dos funcion�rios s�o como se segue:

1� funcion�rio: 2000 reais
2� funcion�rio: 2000 reais
3� funcion�rio: 2000 reais
4� funcion�rio: 100.000 reais
Calculando a M�dia:

100.000 + 2000 + 2000 + 2000 / 4 = 26500
Voc� diria que a m�dia dos sal�rios da empresa � de 26500 reais? N�o, porque o 100.000 reais est� atrapalhando a m�dia real.

Chegamos � conclus�o que temos que pensar em outras solu��es para o c�lculo da Tend�ncia Central de um conjunto de dados. A M�dia Aritm�tica � totalmente sens�vel aos valores que chamamos de outliers, ou pontos fora da curva.

Veremos agora outras maneiras de calcular a tend�ncia central de um conjunto de dados.

A Mediana
Para o c�lculo da Mediana, colocamos os valores dados em ordem crescente e escolhemos aquele valor que � central. Isto � f�cil para quantidades �mpares de dados, pois haver� um n�mero que estar� bem no meio da amostra. Veja um exemplo:

1 1 6 1 5 10 1 1 1
Em ordem crescente:

1 1 1 1 1 1 5 6 10
O valor central � o 1, que � a nossa Mediana.

Para quantidades pares de dados, pegamos os dois valores centrais e calculamos sua M�dia Aritm�tica:

1 1 5 1 2 10 1 6
Em ordem crescente:

1 1 1 1 2 5 6 10
Os valores centrais s�o, respectivamente, o 1 e o 2. A m�dia entre ele � 1,5, a Mediana que quer�amos encontrar.

Perceba que a Mediana � menos suscet�vel aos outliers. L�gico que isso n�o significa que a M�dia Aritm�tica n�o � uma boa Medida de Tend�ncia Central. Se sua distribui��o � est�vel, a M�dia pode ser boa.

Ent�o como saber qual das duas usar? Verifique se os outliers s�o muito grandes e distantes do resto da amostra. Outra regra � que se o tipo de dado for Ordinal, a M�dia n�o � um bom m�todo.

A Moda
A Moda � aquele elemento que mais se repete na distribui��o:

1 1 2 2 2 2 2 3 3 5 5 5
Nessa amostra, o n�mero 2 � o que mais se repete, logo ele � a nossa Moda.

Ent�o, verifique qual � o n�mero que mais se repete na distribui��o, pois pode ser uma maneira honesta de se calcular a Medida de Tend�ncia Central.

Voc� ir� perceber que numa amostra bem distribu�da, a M�dia, a Mediana e a Moda s�o iguais ou possuem valores muito pr�ximos.

Dicas:
Com dados Ordinais usamos Mediana ou Moda;
Utilizamos a M�dia em dados Intervalares, salvo aqueles que possuam outliers;
Desenhe um Histograma, como vimos na aula passada. Verifique se consegue desenhar uma linha parecida com a Normal. Se voc� tiver uma distribui��o normal, o c�lculo da M�dia � um m�todo razo�vel.

<h2>Calcular tend�ncia central</h2>
Quando nossos dados est�o normalmente distribu�dos e sem outliers, qual a melhor maneira de se calcular a tend�ncia central?
R: M�dia serve exatamente para o caso onde a distribui��o � normal e n�o h� muitos outliers na distribui��o

<h2>Dados dispersos</h2>
Quando os dados est�o bastante dispersos, quais s�o as melhores maneiras de se calcular a tend�ncia central?
R: Tanto a Mediana quanto a Moda podem ser boas maneiras de descobrir a tend�ncia central. A m�dia aritm�tica � facilmente afetada por outliers.

<h2>Sobre Moda</h2>
O que � Moda?
R: � o elemento que mais aparece/se repete em uma distribui��o.

<h2>Melhor tend�ncia</h2>
Olhando para essa distribui��o, o que voc� usaria para achar a tend�ncia central?

[1, 1, 50, 50, 50, 50, 50, 50, 50, 60, 60, 65, 70, 200, 250, 300, 700]
R: Nessa distribui��o a m�dia � de 121, a moda e mediana s�o 50.

<h2>Melhor tend�ncia#2</h2>
Na distribui��o abaixo, que representa a medi��o de altura, em metros, de diversas tartarugas marinhas. Qual � a melhor forma de encontrar a tend�ncia central?

[1, 2, 2, 3, 3, 3, 4, 4, 4, 4, 5, 5, 5, 6, 6, 7]

R: Nessa distribui��o a media, moda e mediana, todos, tem o valor 4.

-----------------------------------------------------------------------------------------------------------------
<h1>Se��o 04 - Praticando: M�dia, Mediana e Moda</h1>

Na �ltima aula aprendemos sobre Tend�ncias Centrais: M�dia, Mediana e Moda. Agora veremos este assunto aplicado ao R.

Escrevemos uma sequ�ncia de n�meros quaisquer no R:

> numeros <- c(1, 2, 3, 4, 5)
Revendo: ao digitar "numeros", conseguimos visualizar essa lista:

> numeros
[1] 1 2 3 4 5
Para que o programa calcule a M�dia Aritm�tica desses n�meros, digitamos "mean( )":

> mean(numeros)
[1] 3
A palavra Mean significa M�dia em ingl�s.

Para o c�lculo da Mediana, digitamos "median( )":

> median(numeros)
[1] 3
Nesse caso em particular a M�dia e a Mediana s�o iguais.

Vamos agora gravar uma nova lista de n�meros:

> lista <- c(2, 3, 7, 8, 1, 3, 4, 8, 22, 67, 19)
Calculando a M�dia e a Mediana:

> mean(lista)
[1] 13.09091
> median(lista)
[1] 7
Perceba que o R calcula bem r�pido essas medidas. Neste momento somos n�s que estamos ditando esses dados de entrata. Em aulas futuras saberemos como import�-los de arquivos CSV.

Infelizmente o R n�o possui uma fun��o pr�pria para a Moda, por�m podemos escrev�-la manualmente. Agora n�o � o momento, pois ir� requerer maior conhecimento de R de sua parte e esse n�o � o foco da aula.

Vimos nas aulas passadas que � importante saber se a distribui��o � Normal ou n�o. No R rodamos um Teste de Hip�tese (veremos em outro momento o que � esse teste) para saber se os dados obedecem uma Normal. Para tal digitamos "shapiro.test( )":

> shapiro.test(numeros)
        Shapiro-Wilk normality test
data:  numeros
W = 0.9868, p-value = 0.9672
Devemos observar o valor de "p-value". Se esse n�mero for muito pequeno, algo em torno de 0,05, n�o � Normal. Nesse caso ele � pr�ximo de 1, logo devemos acreditar que � uma Normal.

Fa�amos o teste com "lista":

> shapiro.test(lista)
        Shapiro-Wilk normality test
data:  lista
W = 0.634, p-value = 6.77e-05
Perceba que para "lista" o n�mero � bem pequeno: 6.77e-05 (o "e-05" representa o n�mero 10 elevado a -5, que est� multiplicando 6,77). Isso significa que "lista" n�o � uma distribui��o normal.

Outro m�todo que � de costume ser usado no R � o "summary( )", que nos passa v�rias informa��es importantes como a M�dia e a Mediana:

> summary(lista)
   Min. 1st Qu.   Median    Mean 3rd Qu.    Max.
   1.00    3.00     7.00   13.09   13.50   67.00
Esse m�todo resume o que j� sab�amos anteriormente: M�dia: 13,09 Mediana: 7 Valor m�nimo: 1 Valor m�ximo: 67

Em outras aulas descobriremos o que s�o o 1� e 3� quartis.

Revendo:
Nessa aula vimos na pr�tica como se utiliza o R para: C�lculo de M�dia e Mediana utilizando, respectivamente "mean( )" e "median( )"; Descobrir se a distribui��o � Normal ou n�o utilizando shapiro.test( )": Se p-value for pequeno, n�o � Normal Se p-value for pr�ximo de 1, � Normal; * Resumir as informa��es de uma lista de dados utilizando "summary ( )".

<h2>Fun��o Pr�pria</h2>
Cole o c�digo abaixo no R:

Mode <- function(x) {
     ux <- unique(x)
     ux[which.max(tabulate(match(x, ux)))]
}
Ele cria uma fun��o chamada Mode(), que calcula a moda para uma lista de n�meros.

Teste esse m�todo e diga qual a moda para os n�meros 1, 2, 2, 2, 2, 3, 3, 4, 5, 5, 6, 7.

<h2>Para saber mais: Python Pandas</h2>

Nesse curso estamos vendo a linguagem R muito usada pelos cientistas. No entanto que existe uma outra linguagem n�o menos popular ou importante na �rea de estat�stica e ci�ncia de dados.

O Python est� ganhando o seu espa�o e a biblioteca pandas est� ficando cada vez mais famoso. Atrav�s do pandas podemos criar Data Frames igual no R e analisar os dados. Os nomes das fun��es s�o bem parecidos. Vejo um exemplo como calcular as tend�ncias centrais com pandas:

>>> import pandas
>>> df = pandas.DataFrame([1, 1, 50, 50, 50, 50, 50, 50, 50, 60, 60, 65, 70, 200, 250, 300, 700])
>>> df.mean()
121.0
>>> df.median()
50.0
>>> df.quantile() #moda
50.0
Caso queira aprender mais sobre mais sobre Python existe uma carreira com v�rios curso:

https://cursos.alura.com.br/career/desenvolvedor-python


--------------------------------------------------------------------------------------------------------------
<h1>Se��o 05 - Variabilidade, Dispers�o dos Dados, Outliers e Quartis</h1>

Aplitude
	- Maior menos o menor da distribui��o
	- Primeira maneira para ver o quanto os dados est�o dispersos
	- Se a amplitude � pequeno significa que os n�meros s�o mais pr�ximos da m�dia
	- Se a amplitude � grande significa que os n�meros est�o mais dist�ntes da m�dia

� necess�rio sempre "limpar" os dados
Formas de limpar dados
	- Ordenar os n�meros e tirar os extremos

Divis�o por Quartis
	- Dividir a distribui��o em 3 partes
	- 25 % os extremos e 50% o centro.

3 3 6 7 7 10 10 10 11 13 30
11/4 = 2..= 3

O terceiro elemento � o cara que divide a distribui��o

3.11/4 = 33/4 = 8.. = 9
O nono elemento � o cara que divide a outra parte da distribui��o

E ent�o descarta o primeiro quartil e o terceiro quartil

Boxplot
	- Gr�fico que mostra os 50% da distribui��o
	- � poss�vel fazer a mediana do boxplot

Ol�! Na aula passada, n�s discutimos sobre m�dia, mediana e moda. Agora, vamos usar essas ideias para o nosso dia a dia. Aqui, eu tenho um cen�rio.

Imagine que eu trabalhe em uma f�brica e essa f�brica tem pessoas que consertam aparelhos. Eu tenho o JO�O e o JOS�, que s�o dois candidatos a uma vaga que eu tenha aberto em minha empresa. Eu tenho um n�mero sobre essas pessoas:

Jo�o

| Frequ�ncia | Aparelhos Consertados |
|------------|-----------------------|
| 1          | 7                     |
| 1          | 8                     |
| 1          | 9                     |
| 2          | 10                    |
| 2          | 11                    |
| 1          | 12                    |
| 1          | 13                    |
Jos�

| Frequ�ncia | Aparelhos Consertados |
|------------|-----------------------|
| 2          | 3                     |
| 1          | 6                     |
| 2          | 7                     |
| 3          | 10                    |
| 1          | 11                    |
| 1          | 13                    |
| 1          | 30                    |
O Jo�o em um dia consertou sete aparelhos; em um outro dia, ele consertou oito; em dois dias ele consertou dez; em dois dias ele consertou 11 e assim por diante. Ent�o, eu tenho a quantidade de aparelhos que ele conserta por dia e a quantidade de vezes em que isso aconteceu.

E a mesma coisa para o Jos�: eu tive dois dias em que o Jos� conseguiu consertar tr�s aparelhos; eu tive tr�s dias em que o Jos� consertou dez aparelhos; eu tive um dia em que o Jos� consertou 30, ele estava super produtivo.

Agora, a pergunta �... Eu tenho Jo�o e Jos� e uma vaga s� aberta, quem eu contrato? Qual dos dois eu escolho?

J� que na aula passada, em que voc�s aprenderam m�dia, mediana e moda, a gente poderia tentar usar isso. Por exemplo, a gente poderia tentar descobrir a m�dia de consertos do Jo�o por dia, a m�dia de consertos do Jos� por dia, e ver qual dos dois tem a m�dia maior, porque eu quero contratar o cara que conserta mais aparelhos.

S� que nos n�meros que eu dei para voc�s, se voc� calcular tanto a m�dia, quanto a moda, quanto a mediana dessas duas distribui��es, voc� vai ver que o valor � 10. Exatamente 10. Ou seja, para m�dia, mediana e moda, esses caras s�o id�nticos!

Qual dos dois eu contrato?

Eu estou falando isso porque a m�dia � uma �tima maneira de te dar a tend�ncia central daquela distribui��o, mas ela n�o te explica muita coisa sobre como esses dados est�o dispersos. Porque eu quero saber que o cara conserta 7 aparelhos e mais ou menos tr�s por dia. Essa � a m�dia dele. Esse mais ou menos tr�s, essa informa��o n�o est� nem na m�dia, nem na mediana, nem na moda. A gente tem que achar uma maneira de tentar descobrir o quanto a nossa distribui��o est� espalhada para complementar a informa��o da m�dia.

Vamos come�ar da maneira mais simples, que � a seguinte: Eu poderia, por exemplo, pegar o maior valor que apareceu para mim e subtrair do menor valor. Eu vou chamar isso de amplitude.

A amplitude do Jo�o � 13-7=6.

J� a do Jos� � 30-3=27.

O 6 e o 27 me d�o uma no��o do quanto esses dados est�o espalhados.

Nesse exemplo, o Jos� est� bastante espalhado - porque eu tenho n�meros grandes e n�meros pequenos - ent�o, a amplitude � muito grande. J� o Jo�o tem uma consist�ncia melhor, ele sempre faz mais ou menos a mesma quantidade por dia, por isso o valor dele � 6.

S� que essa maneira de calcular, simples assim como mostrei, o maior elemento da minha distribui��o (limite superior) menos o menor elemento de minha distribui��o (limite inferior) � uma maneira muito simples porque ela � f�cil de ser enganada.

� s� olhar, por exemplo, para o Jos�. Ele conserta 3, 6, 7, 10, 11, 13 e, de repente, 30. Ele teve um dia excepcional no trabalho dele que fez com que ele consertasse 30 aparelhos. Mas aconteceu uma vez, foi uma exce��o, n�o acontece sempre. Justamente porque esse 30 est� aqui, ele afetou o valor da amplitude.

Est� a� uma outra coisa para voc� se preocupar no seu dia a dia: sempre que voc� olha uma distribui��o, voc� tem que se preocupar com esses dados que est�o muito fora da distribui��o, muito fora da curva. Em ingl�s, n�s chamamos isso de outlier, o cara que est� muito fora do resto dos dados. E o outlier - eu comentei com voc�s na aula da m�dia - ele atrapalha o c�lculo. (Lembrem do exemplo do sal�rio. O cara ganha R$2.000; outro ganha R$2.000; outro ganha R$50.000. Esse R$50.000 atrapalha.) Esse outlier de 30 atrapalha o nosso c�lculo da amplitude. Essa � uma maneira ruim, portanto, de calcular a dispers�o dos nossos dados.

Vamos l�. Antes de chegarmos a uma maneira interessante de calcular essa dispers�o a primeira coisa que eu quero discutir com voc�s � como filtrar esses outliers. Como jogar esse 30 fora? Como jogar esse 3 fora? Porque esse 3 tamb�m � um outlier. Voc� percebe que 6, 7, 10 se repetem muito mais do que 3. No Jos� � mais dif�cil dizer, mas o 7 tamb�m pode ser um outlier. Um outlier pode ser um cara muito grande ou um cara muito pequeno. Ent�o, eu preciso de uma maneira "procedimental", eu preciso de um jeito mec�nico de jogar fora esses outliers.

Como fazemos isso? A gente usa a distribui��o por quartis. Eu vou dividir minha distribui��o em 4 peda�os.

Por exemplo, o Jos�. Eu tenho aqui a tabela de frequ�ncia e eu vou escrever todos os n�meros dessa tabela:

3 3 6 7 7 10 10 10 11 13 30
Ent�o, essa � a distribui��o do Jos�. Eu quero dividir ela em 4 peda�os. Ent�o, vamos contar quantos elementos eu tenho: 11 elementos.

Vamos l�, eu quero dividir isso em 4, mas n�o em 4 partes "exatamente iguais". Eu quero p�r 25% para esquerda, 25% para direita e 50% no meio. Porque se eu tiver 25% para esquerda, 25% para direita, e o que est� no meio; perceba que eu joguei os outliers fora, porque os outliers ou s�o n�meros muito pequenos ou s�o n�meros muito grandes. E a� a gente acredita que esses n�meros muito pequenos v�o morrer nesses 25% primeiros e os n�meros muito grandes v�o morrer nos 25% do fim. E eu vou usar somente os 50% do meio da minha distribui��o, e ali eu tenho mais ou menos a certeza de que eu n�o vou ter outlier. Isso � o que chamamos de distribui��o por quartis.

Agora, vamos calcular os lugares exatos. Primeira coisa, eu conto o n�mero de elementos. Eu tenho 11 elementos aqui e eu preciso achar a posi��o do primeiro quartil. E para descobrir isso � f�cil. Eu pego o total de elementos da minha distribui��o, que s�o 11 e divido por 4, que s�o os n�meros de quartis. Isso aqui me d� 2,75, que arredondado para cima d� 3. Voc� achou a posi��o do primeiro quartil.

3 3 (6) 7 7 10 10 10 11 13 30
Agora, n�s precisamos achar o que chamamos de terceiro quartil. Como que eu fa�o isso? 3n/4, porque eu quero que 3/4 dos meus dados estejam antes desse terceiro quartil. Ent�o 33/4=8,25, que eu vou arredondar para 9.

3 3 6 7 7 10 10 10 (11) 13 30
E o que est� no meio � o que a gente acaba usando nas nossas contas por que 7, 7, 10, 10, 10 n�o tem outlier e isso representa melhor a nossa distribui��o.

Isso � o que chamamos de distibui��o por quartis. A vantagem disso � conseguir eliminar os nossos outliers. Ent�o pense nisso sempre que voc� tiver uma distribui��o que tenha esses dados fora da curva. E esse tipo de informa��o � t�o comum que a gente j� tem um gr�fico que � muito usado no dia a dia, que � o gr�fico que n�s chamamos de boxplot. Vou mostrar para voc�s como ele funciona.

A ideia do boxplot � passar para a gente todas essas informa��es: o primeiro quartil, o terceiro quartil, a m�dia... em um �nico desenho.

Vamos desenhar esse boxplot e vamos desenhar para o Jos�. Eu tenho aqui um gr�fico de eixo e, para mim, s� importa o eixo y nesse momento. Vou come�ar colocando o menor valor da minha distribui��o que � o 3.

Ent�o eu tenho o 3 aqui e no gr�fico eu vou representar por um tra�o simples. O pr�ximo n�mero que eu vou representar � o n�mero do primeiro quartil que � o n�mero 7. Imagine a posi��o do 7 no gr�fico, onde eu vou ter um tra�o. E a gente at� liga esse tra�o com o tra�o do n�mero 3. Voc� j� vai entender o desenho como um todo.

O pr�ximo que eu vou fazer � representar o terceiro quartil que � o 11. Coloco o 11 no gr�fico e agora eu vou fechar uma caixa.

L� em cima eu vou representar o maior valor da minha distribui��o que nesse caso � 30 - valor bem fora da curva.

E no meio desse gr�fico, eu vou representar tamb�m a nossa mediana, que nessa nossa distribui��o � o 10.

Ent�o, olhem s� o que � o tal do boxplot; em um simples gr�fico, voc� sabe:

o menor valor da sua distribui��o (limite inferior);
o maior valor da sua distribui��o (limite superior);
o primeiro quartil;
o terceiro quartil;
a mediana.

<img src="3.png"/>

A mesma informa��o que a gente fez naquele desenho da lista de n�meros, agora est� em um gr�fico boxplot.

Ent�o, esse gr�fico � bastante famoso por causa disso, porque s� de bater o olho, voc� tem ideia de como sua distribui��o funciona.

Veja s� que a dist�ncia no gr�fico do n�mero 30 nos d� a no��o de que eu tenho outliers. O outlier inferior � pequeno, porque a dist�ncia no gr�fico � pequena, mas em rela��o ao limite superior ela � grande, ent�o eu tenho outliers, portanto eu preciso pensar realmente em quartis.

Nesse cap�tulo, era isso que eu queria mostrar para voc�s. Que a m�dia quando eu quero comparar duas distribui��es n�o � suficiente, porque a m�dia me d� a tend�ncia central, mas eu preciso saber tamb�m o quanto esses dados variam dentro da distribui��o. E assim, come�amos a discuss�o de como chegar nessa vari�ncia.

Primeiro, mostrei aquele c�lculo simples de amplitude (o limite superior menos o limite inferior), mas a gente discutiu que ela � facilmente influenciada pelos outliers.

A� chegamos at� a distribui��o por quartis, cuja ideia � eliminar esses outliers, excluindo 25% dos dados da esquerda e 25% dos dados da direita e usando os 50% que est�o no meio da distribui��o.

Mostrei como calcular o primeiro quartil e o terceiro quartil:

para o primeiro quartil, pegue o tamanho da sua distribui��o e divida por 4, achando um n�mero que, se der quebrado, deve ser arredondado para cima.
a mesma coisa para o terceiro quartil, s� que aqui eu multiplico por 3n, porque eu quero o terceiro quartil, ent�o 3n/4, se o resultado der quebrado, deve ser arredondado para cima.
Calculei tamb�m a mediana.

E, dessa forma, eu consigo desenhar meu boxplot. E s� de olhar meu boxplot, eu tenho uma no��o de como � a distribui��o.

Fica para voc�s como li��o de casa desenhar o boxplot do Jo�o.

Veja s�, o Jo�o tem um caso engra�ado. O limite inferior � 7 e qual � o primeiro quartil? A gente vai ter que calcular. Vai ficar de li��o de casa para voc�. Ent�o, coloquem at� um boxplot ao lado do outro, e voc� vai ver que isso vai facilitar a sua compara��o.

Nos pr�ximos cap�tulos eu vou chegar nos finalmentes, em como calcular a vari�ncia dessas duas distribui��es.


<h2>Sobre Outliers</h2>
O que s�o outliers?
R: S�o n�meros extremos, geralmente muito grandes ou muito pequenos, no meio de uma distribui��o. Geralmente s�o n�meros que eliminamos na hora de analisar, porque s�o casos extremos.
Por exemplo, colocar o sala�rio do S�lvio Santos no meio dos sla�rios dos brasileiros, alterar� o valor da m�dia.


<h2>Voc� conhece boxplot?</h2>
Quais s�o as informa��es que aparecem em um boxplot?
R: Em um boxplot, exibimos: Mediana, Primeiro Quartil, Terceiro Quartil, Maior e Menor elementos da distribui��o.

<h2>Quais quartis</h2>
Suponha a seguinte distribui��o
20 21 22 22 23 24 24 26 28
Qual � o primeiro e o terceiro quartil?
R:Se voc� usar o R para fazer esse calculo, a resposta ser� 22 e 24 pois ele tenta arredondar.

Lembre-se que n�o h� a resposta "precisa" pra isso. A ideia dos quartis � voc� ter 50% dos dados entre o primeiro e o terceiro. Alguns matem�ticos optam por arredondar pra cima, outros por calcular a m�dia. O importante aqui � eliminar os outliers.

-------------------------------------------------------------------------------------------------
<h1>Se��o 06 - Praticando: Boxplots</h1>

Ol�! Agora que voc� aprendeu porque quartis s�o legais e o que � um boxplot, vamos fazer isso no R.

E voc� vai ver que o R est� mais que pronto para isso, ent�o a gente n�o vai ter trabalho nenhum.

Vou criar uma lista qualquer de n�meros, inventando quaisquer n�meros, por exemplo:

> numeros <- c (1, 3, 5, 6, 10, 19, 23, 5, 7, 89, 15, 14, 22, 23, 32, 23, 37)

E se eu quiser ver o primeiro quartil, o terceiro quartil eu j� mostrei o summary, s� que agora voc�s entendem que esse first quartile e esse third quartile que aparecem a�.

> summary (numeros)

Ent�o o primeiro quartil � 6; o terceiro quartil � 23. E se voc� quiser ver o boxplot, digite boxplot e a lista e ele automaticamente desenha para mim o boxplot. Simples assim e sem nenhum segredo.

> boxplot (numeros)

�bvio que voc� pode customizar esse gr�fico. Como voc� vai descobrir isso? Olhando o manual do boxplot.

> ?boxplot

Dando espa�o, o texto desce, e a� voc� vai ler e entender como ele funciona.

S� que muito r�pido, porque o R faz tudo para a gente.

Vou aproveitar e mostrar um truque que eu uso bastante. � o seguinte: eu gerei o gr�fico aqui e desenhei o boxplot mas eu n�o quero ele aqui; eu quero em um arquivo para eu colocar isso em um documento meu, eventualmente em um paper que eu estou escrevendo, ent�o eu quero salvar isso em uma imagem. Como eu fa�o? F�cil! Eu vou usar a fun��o que se chama png.

png recebe um atributo, um par�metro: file. E eu vou abrir aspas e aqui eu vou passar para ele o caminho de onde eu vou salvar.

> png(file=" "

Eu vou abrir uma outra aba e vou descobrir em que diret�rio eu estou. Eu estou em User/alura/.

> png(file="User/alura/boxplot.png"

E eu posso passar para ele at� o tamanho da imagem: width de 700 pixels e o height de 700.

> png(file="User/alura/boxplot.png", width=700, height=700)"

Eu coloquei uma aspas sobrando e ele n�o gostou. Errei. Matei o comando com o comand c [d�vida aqui 02'24], voltou e eu vou apagar essa aspas.

Como que eu fiz ele escrever automaticamente para mim? Seta para cima. D� uma olhada: a seta no R vai me mostrando os �ltimos comandos que eu rodei.

Ent�o, de novo: uso o png, com file eu passo o diret�rio, width eu passo o caminho, height eu passo a altura, sem essa aspas que estava sobrando na linha de cima e dou um enter.

> png(file="User/alura/boxplot.png", width=700, height=700)

Ele entendeu. Ele sabe o que ele tem que escrever nesse arquivo.

Agora eu vou fazer o boxplot.

> boxplot(numeros)

D� uma olhada, ele n�o fez nada. Por qu�? Porque, agora, ele n�o tem que plotar na tela para mim, ele tem que plotar no arquivo.

Legal! J� fiz tudo o que eu queria nesse arquivo. Preciso falar para ele que acabei, pode salvar. Eu fa�o isso com:

> dev.off()

Ele me desce a� 1, que � sucesso. E se eu vier aqui listar, d� uma olhada que eu tenho o boxplot.png. Se eu abri-lo:

Alura: - aluraS open boxplot.png

Ele vai abrir para mim a imagem:

<img src="4.png"/>

E, d� uma olhada, a imagem est� salva no arquivo.

Por que ele n�o salvou de primeira aqui, quando eu fiz > boxplot(numeros)? Ele esperou, porque quando eu estou desenhando uma imagem no R, eu posso ir passando comandos na linha de baixo, que acrescentam coisas � imagem. Eu poderia mudar a cor da imagem ou de um tra�o qualquer ali posteriormente. O R me permite fazer. Ent�o, eu vou manipulando essa imagem e quando eu estou satisfeito, eu fa�o > dev.off(), dou um enter, e ele salvou a imagem para mim.

Veja s� que simples.

De novo, a aula com R � sempre bem r�pida, porque voc� j� conhece a teoria e a aplica��o aqui � natural.

Ent�o, eu mostrei para voc�s como desenhar um boxplot, usando a fun��o boxplot, e mostrei tamb�m como salvar em um arquivo.


<h2>dev.off?</h2>
Para que serve o comando dev.off()?
Para enviar o buffer para o arquivo de imagem previamente configurado.
Para finalmente salvarmos a imagem que est� sendo desenhada na "mem�ria" do R, no arquivo previamente informado.


-------------------------------------------------------------------------------------------------------
<h1>Se��o 07 - Vari�ncia e Desvio Padr�o</h1>

<h2>Entendendo melhor a distribui��o</h2>

Pq s� a m�dia nao � suficiente quando quero comparar duas distribui��o
Pq a m�dia n�o fala quanto os dados est�o espalhados.
� necess�rio para comparar duas distribui��es

Calcular a dist�ncia da m�dia de cada n�mero e depois fazer a m�dia de todos os resultados para encontrar a m�dia da dispers�o dos dados.

Ex:
1 2 9
M�dia: 4
Elevado ao quadrado por conta do sinal negativo
= (4-1)^2 + (4-2)^2 + (4-9)^2 / 3
= 9 + 4 + 25 / 3 = 38/3 +/- 13 ----> Varian�a = raiz de 13 +/- 3.5 ----> Desvio Padr�o

O mais import�nte � a ideia, o desvio padr�o tenta descobrir a dist�ncia em rela��o a m�dia.
Isso da a dispers�o da nossa distribui��o

Desvio Padr�o = 1.73
    Jo�o	M�dia: (7 + 8 + 9 + 10 + 10 + 11 + 11 + 12 + 13) / 9 =  10,11
		Vari�ncia: (10,11 - 7)^2 + (10,11 - 8)^2 + (10,11 - 9)^2 + (10,11 - 10)^2 + (10,11 - 10)^2 + (10,11 - 11)^2 + (10,11 - 11)^2 + (10,11 - 12)^2 + (10,11 - 13)^2 = 
Freq	Aparelhos Consertados
1	7
1	8
1	9
2	10
2	11
1	12
1	13

    Jos� - Desvio Padr�o = 7.02
Freq	Aparelhos Consertados
2	3
1	6
2	7
3	10
1	11
1	13
1	30


Jo�o � mais constante que o Jos�


	
Ol�! Na aula passada, come�amos a discutir porque que s� a m�dia n�o � suficiente quando eu quero comparar duas distribui��es. Porque a m�dia por si s� n�o me fala o quanto a distribui��o est� espalhada. Ela me d� a tend�ncia central, mas n�o me fala quanto os dados est�o espalhados a partir dessa m�dia.

E eu preciso saber isso para conseguir comparar o Jo�o e o Jos�. Qual desses dois ser� que tem um ritmo melhor de trabalho? Qual tem uma frequ�ncia melhor?

Na aula passada come�amos a tentar resolver esse desafio e chegamos naquela f�rmula da amplitude, em que eu pegava o limite superior subtraia o limite inferior que resultava em um n�mero, s� que vimos que os outliers atrapalham. O 30 do Jos�, em particular, atrapalhou bastante a gente.

Come�amos a pensar em como eliminar esses outliers e chegamos na ideia da distribui��o por quartis. Joga os outliers da esquerda para fora, joga os outliers da direita para fora e uso os dados que est�o no meio.

�timo! Agora, vamos l�.

Vamos tentar pensar em uma maneira "elegante" de achar essa diferen�a, esse desvio que os n�meros tem da m�dia.

Para isso eu n�o vou usar nem o Jo�o, nem o Jos�. eu vou usar uma distribui��o menor para facilitar os nossos c�lculos.

Imagine que eu tenha uma distribui��o (1, 2, 9); e a m�dia � 4.

Eu quero pensar, ent�o, como eu posso saber a vari�ncia m�dia entre os n�meros. Uma boa ideia seria ver, por exemplo, a dist�ncia que o 1 tem da m�dia, que � 4. Ent�o o 1 est� a 3 pontos - irei chamar de pontos - da m�dia. O 2 para 4 faltam 2. O 9 para 4 faltam 5.

Ent�o, a minha ideia vai ser essa: vou calcular a dist�ncia de cada ponto da m�dia e a�, calcular a m�dia desse n�mero. � a m�dia da dispers�o dos dados.

Para essa distribui��o fica f�cil: (4-1)+(4-2)+(4-9)/3

Divido por 3 porque eu tenho 3 elementos na minha distribui��o.

Isso vai me dar: 3+2-5/3

O resultado ser� 0.

Est� a� o primeiro problema da nossa f�rmula, porque eu tenho n�meros � esquerda, n�meros � direita e quando eu subtraiu eles da m�dia, eu acabo tendo n�meros negativos. E o n�mero negativo pode cancelar o n�mero positivo. E eu n�o quero isso. Eu quero que cada ponto do meu gr�fico tenha influ�ncia nesse valor final.

Vamos tentar melhorar nossa ideia. Como que eu posso fazer para eliminar n�meros negativos?

Uma maneira f�cil para isso � p�r esses n�meros ao quadrado. Qualquer n�mero ao quadrado � sempre positivo!

(4-1)^2+(4-2)^2+(4-9)^2/3

3^2+2^2+(-5)^2/3

9+4+25/3

38/3 ~= 13

(Voc� fa�a a conta direito, com 2, 3, 4 casas decimais. Aqui, eu estou arredondando para facilitar.)

Eu cheguei no n�mero 13. Esse 13 � minha primeira tentativa de dizer o quanto os n�meros est�o dispersos dessa m�dia, na m�dia.

S� que o problema � que como eu elevei esses n�meros ao quadrado, eu n�o tenho um n�mero em uma dimens�o que eu quero. Ent�o, se eu elevei ao quadrado, agora eu vou resolver isso calculando a raiz.

Se eu pegar esse 13 e calcular a raiz dele, eu vou ter aproximadamente 3,5.

raiz de 13 = 3,5

Agora, esse 3,5 me � �til, porque ele est� me dizendo que os n�meros dessa distribui��o tem a m�dia 4 �3,5. Ent�o, na m�dia, nessa distribui��o, os n�meros est�o espalhados por 3,5 para l� e para c�.

Esse n�mero 3,5 tem um nome bonito na Estat�stica que voc� j� conhece: desvio padr�o.

O 13, esse n�mero intermedi�rio que n�s usamos para o c�lculo do desvio padr�o tamb�m possui um nome em Estat�stica: vari�ncia.

Veja s� que usamos a vari�ncia para chegar no desvio padr�o, e o desvio padr�o d� para a gente o quanto aqueles n�meros est�o dispersos.

Mais importante do que a f�rmula - porque a f�rmula � mec�nica e voc� decora - o importante � a ideia de como o desvio padr�o funciona. Ele tenta descobrir a dist�ncia daquele ponto em rela��o � m�dia. Ele faz isso para todos os pontos e calcula a m�dia disso a�. E, assim, temos o desvio padr�o. Isso d� para a gente a dispers�o da nossa distribui��o. E, agora, eu consigo comparar.

Vai ficar de li��o de casa para voc�, calcular o desvio padr�o e a vari�ncia do Jo�o e do Jos�.

Mas voc� vai ver que na hora de calcular, voc� vai chegar nos seguintes n�meros:

Jo�o 1,73

Jos� 7,02

O que esses n�meros me dizem?

Eles me dizem que o Jo�o � mais consistente, porque o desvio padr�o dele � MENOR. Ent�o a m�dia � 10�1. Ent�o, quando eu contratar o Jo�o a chance que eu tenho dele consertar de 10, -1 para a esquerda, -1 para direita � grande, porque esse � o desvio.

Agora, o Jos� � um cara mais complicado. A m�dia dele � 10, mas ele pode ter um dia muito bom e ele consertar 17; mas ele pode ter um dia muito ruim, e consertar s� 3.

Ent�o, talvez, contratar o Jo�o te d� mais seguran�a, porque o Jo�o vai fazer 10�1 e o Jos� 10�7.

Nesse caso em que eu quero maximizar o n�mero de consertos, talvez o JO�O seja uma aposta melhor.

Veja s�, que n�s t�nhamos duas distribui��es na aula passada - Jo�o e Jos� -, a m�dia era igual - ent�o, para mim, eles pareciam iguais -, mas olha s� como o desvio padr�o de cada um deles � diferente.

Perceba isso: quando for comparar duas distribui��es, n�o olhe s� a tend�ncia central, olhe tamb�m o desvio padr�o desses dados e voc� vai entender como aquela distribui��o est� se comportando.

Nessa aula foi isso: DESVIO PADR�O e VARI�NCIA.

<h2>Desvio padr�o pequeno?</h2>
Um desvio padr�o pequeno indica o qu� em rela��o aos dados?
R: Que os dados est�o pr�ximos da m�dia

<h2>Desvio padr�o alto?</h2>
Um desvio padr�o alto indica o qu� em rela��o aos dados?
R: Um desvio padr�o alto indica que os dados est�o dispersos.

<h2>Por que elevamos a diferen�a ao quadro para calcular a vari�ncia?</h2>
R: Para que n�meros negativos n�o interfiram no resultado afinal. Ao elevar ao quadrado, todos ficam necessariamente positivos.

----------------------------------------------------------------------------------------------------
<h1>Se��o 08 - Praticando: Desvio Padr�o</h1>

Ol�! Ent�o, acabamos de ver um pouquinho sobre vari�ncia e desvio padr�o.

Vamos aplicar isso no R agora.

E voc�, provavelmente, induziu que � f�cil. O R tem tudo isso pronto. Est� vendo como foi uma boa ideia usar o R?

Vamos l�!

Criando uma lista de n�meros quaisquer novamente:

> numeros <- c(1, 2, 3, 5, 6, 7, 8, 11, 2, 3, 44, 55, 67, 12, 34, 56)

Se eu quiser calcular a vari�ncia:

> var(numeros)

E est� aqui a nossa vari�ncia: 531.

Mas, a gente sabe que a vari�ncia sozinha n�o fala muita coisa para gente. Ent�o eu vou guardar isso em uma vari�vel que eu vou chamar de vari�ncia.

> variancia <- var(numeros)

E a�, eu vou calcular a raiz quadrada da vari�ncia:

> sqrt(variancia)

Isso me d� o meu desvio padr�o. A gente sabe que o desvio padr�o � a raiz quadrada da vari�ncia.

Mas eu preciso fazer em dois passos? Claro que n�o. O R tem pronto:

> sd(numeros)

Que me d� o mesmo valor; o resultado tem que bater.

Ent�o calcular o desvio padr�o � f�cil: use > sd (standard deviation), passe a lista e ele calcula para mim.

Para deixar mais legal aqui, o que eu vou mostrar agora para voc� � como ler dados de um arquivo. Porque at� ent�o n�s estamos criando esses n�meros na m�o, mas eu quero ler de um arquivo. Ent�o, imagina que o meu teste estat�stico, todo esse meu c�digo que leu com Estat�stica, ele usa dados que v�m de um lugar. Esse algum lugar pode ser um arquivo .csv, que � aquele formato bastante comum na Computa��o, que s�o coisas separadas por v�rgulas.

Estou aqui em um diret�rio qualquer, e eu vou criar um arquivo que eu vou chamar de numeros.csv.

Eu usei o vi as hex que � um editor de texto; voc� pode usar o bloco de notas, o que voc� quiser.

E aqui eu vou colocar alguns valores, por exemplo:

|1|2| |2|4| |3|6| |4|8|

Vou salvar esse arquivo e, d� uma olhada, se eu imprimir esse arquivo est� l�:

Alura:- aluraS vi numeros.csv
Alura:- aluraS cat numeros.csv 
1,2
2,4
3,6
4,8

Alura:- aluraS
Agora, eu estou no R:

Alura:- aluraS R

Eu quero ler esses n�meros. Como eu fa�o? Use read, csv - que � o formato -, abro par�nteses e vou passar o par�metro para ele - file -, /Users, /alura - que � o diret�rio em que estou, eu vou at� dar um pwd para confirmar, /numeros.csv.

> read.csv(file="/Users/alura/numeros.csv")

Se voc� estiver no Windows �: c:...diret�rio...nome do arquivo. � o caminho completo.

Essa linha aqui: > read.csv(file="/Users/alura/numeros.csv") vai ler todo o conte�do desse numeros.csv. S� que eu tenho que guardar isso em algum lugar. Vou guardar em uma vari�vel. O m�todo csv retorna para gente uma estrutura de dados com essas coisas.

Ent�o se eu fizer > nums e der um ENTER, d� uma olhada:

> nums

|---| X1 | X2 | | 1 | 2 | 4 | | 2 | 3 | 6 | | 3 | 4 | 8 |

Em X1, ele colocou a primeira coluna que era 2, 3 e 4; em X2, a segunda coluna, 4, 6 e 8.

E eu posso, agora, por exemplo, exibir s� uma coluna:

> nums$X1 [1] 2 3 4

Veja s�, uma coisa nova no R. O $ (d�lar) quando eu tenho essa estrutura que � um dataset, eu consigo pegar uma coluna usando o $.

Posso tamb�m tra�ar o histograma de uma coluna s�:

> hist(nums$X1)

<img src="5.png"/>

Ele me desenhou o histograma e assim por diante.

Ent�o assim que a gente l� de arquivos .csv: read.csv. Eu consigo ler de um monte de lugares diferentes, e a� voc� olha no manual do R.

Nessa aula eu mostrei para voc�s vari�ncia e desvio padr�o. Simples! O R faz toda a m�gica para gente.

<h2>Fun�a� para Desvio Padr�o</h2>
Qual a fun��o que calcula desvio padr�o no R?
R: sd()

<h2>R e arquivos csv</h2>
O que read.csv() faz?
R: L� um arquivo csv e transforma em uma estrutura de f�cil manupula��o no R.

<h2>Dollar no Data Frame</h2>
O que o sinal $ significa em nums$X1?
R: Ela pega a coluna X1 existente em nums


-------------------------------------------------------------------------------------------------
<h1>Se��o 09 - Popula��o x Amostra: Pensando em um estudo</h1>

Estudo para descobrir qual time brasileiro tem mais torcida, ou qual presidente tem mais votos.
Voc� ter� que ir para rua perguntar.
Para saber com exatid�o ter� que perguntar para todos os habitantes brasileiros.
� imposs�vel conseguir todas essas pessoas e talv�s seja muito caro para falar com essa quantidade de habitantes.
Querer entender como uma determinada popula��o se comporta.
Mas n�o tenho acesso a popula��o inteiro.
� necess�rio encontrar a Amostra.
Conjunto de pessoas que eu arranco da popula��o e fa�o o estudo em cima dessa Amostra.
Vou conseguir generalizar para essa popula��o.
Se eu quiser saber qual o time mais popular, posso falar com uma Amostra da popula��o.
Mas n�o � t�o f�cil.
Uma forma f�cil de errar � conseguir uma amostra errada.
Ex: Entrevistar pessoas conhecidas, provavelmente todos ir�o torcer para times parecidos.
Como estat�stico � necess�rio escolher uma amostra ideal.

A Amostra precisa ser Randomica.
Tem que ser aleat�rio. Qualquer um que estiver na popula��o tem que ter chances de ser escolhido.
Amotra Randomica.

Cen�rio menor. 500 alunos e escolher de maneira aleat�rio essa amostra.
E mesmo assim � complicado.


Amostra Estratificada
	- Separar per�odos para pegar amostras

M�dia da Amostra � igual a m�dia da Popula��o

A vari�ncia da popula��o � maior que a da amostra, por conta disso � subtra�do 1 para a divis�o da vari�ncia.


Ol�, ent�o agora voc� aprendeu um monte sobre estat�stica. J� aprendeu m�dia, mediana, moda, vari�ncia, desvio padr�o, distribui��o por Quartis etc. Est� na hora de come�ar a aplicar isso, n�? Porque, no fim das contas, pra qu� voc� quer estat�stica? Voc� quer usar estat�stica pra entender como determinado grupo se comporta.

Ent�o, imagine que voc� quer fazer, por exemplo, um estudo pra descobrir qual � o time de futebol brasileiro que tem mais torcida, ou qual � o prefeito ou presidente que vai ser mais votado etc. Voc� vai ter que ir pra rua e falar com essas pessoas. Ent�o, por exemplo, se voc� quer descobrir para quem a pessoa torce, voc� vai ter que perguntar:

Qual � o seu time de futebol favorito?

E � a� que entra o problema. Porque, veja s�, imagine que voc� quer descobrir qual � o time de futebol mais popular no Brasil inteiro. Pra saber isso com exatid�o, voc� teria que perguntar para os nossos mais de 200 milh�es de brasileiros para que time eles torcem. � imposs�vel, certo? Imposs�vel por v�rios motivos:

� imposs�vel conseguir 200 milh�es de pessoas
mesmo que voc� conseguisse, talvez isso seja muito caro. Voc� vai ter que pagar um ser humano ou uma m�quina, qualquer coisa do tipo, pra falar com 200 milh�es de pessoas.
O primeiro problema que eu quero mostrar pra voc�s � que a gente quer entender como uma determinada popula��o se comporta, veja a palavra aqui popula��o, o conjunto total de pessoas que eu quero estudar, mas n�o tenho acesso a essa popula��o inteira. Como fazer? O grande segredo da estat�stica � achar a amostra. A amostra � um conjunto de pessoas que eu arranco dessa popula��o - � um conjunto muito menor, obviamente, fica mais barato - e fa�o meu estudo em cima dessa amostra. E a ideia � que, se eu selecionei bem essa amostra eu vou conseguir generalizar os n�meros que eu encontrei pra minha popula��o.

Ent�o, � assim que fazemos. Se eu quiser descobrir, por exemplo, qual � o time mais popular do Brasil, eu n�o preciso falar com os 200 milh�es de brasileiros. Eu posso eventualmente falar com mil ou dois mil brasileiros e tentar generalizar isso. S� que n�o � t�o f�cil assim quanto parece. No primeiro dia de aula, eu comentei aquela frase, que voc�s j� devem ter ouvido falar:

Existem mentiras, grandes mentiras e estat�sticas

Uma maneira muito f�cil de voc� errar � justamente escolhendo uma m� amostra. Por exemplo, imagine o seguinte: que voc� quer descobrir de novo o time de futebol preferido do Brasil. A� voc� decide que vai entrevistar s� a fam�lia. E pergunta:

M�e,pra que time voc� torce? Pai, pra que time voc� torce? Irm�o, pra que time voc� torce?

Muito provavelmente, todo mundo torce pro mesmo time, e a� voc� vai descobrir que, no Brasil, todo mundo torce pro time A ou pro time B. Por qu� isso aconteceu? Porque eu escolhi a amostra errada. Ent�o, voc� como pesquisador, como estat�stico, tem que escolher a amostra de maneira decente, de maneira correta.

Dicas pra isso: como eu escolho a minha amostra? Idealmente, ela tem que ser rand�mica. Da seguinte forma: eu tenho a minha popula��o inteira e eu quero pegar peda�os dessa popula��o. Mas, eu n�o quero pegar peda�os espec�ficos, por exemplo, eu n�o quero falar com meu irm�o, porque o meu irm�o est� perto de mim. Tem que ser rand�mico, ou seja, qualquer um que est� dentro dessa popula��o tem que ter a mesma chance de ser escolhido nesse meu momento l� de escolher a minha amostra: isso � uma amostra rand�mica. O que tamb�m n�o � algo t�o f�cil, dependendo do estudo que voc� quer fazer.

Imagine que voc� queira fazer um estudo com os 200 milh�es de brasileiros. Pra que isso acontecesse de verdade, idealmente voc� pegaria a lista telef�nica, folhearia, pararia numa folha do meio e escolheria um nome. E a� voc� escolheu algu�m de maneira rand�mica. Mesmo assim, talvez voc� ainda tenha um vi�s, porque talvez haja uma pessoa que mora numa regi�o muito pobre, que n�o tenha telefone, e cujo nome n�o esteja na lista. Mas, � uma maneira.

Agora, vamos imaginar um cen�rio menor. Voc� quer fazer um estudo na sua escola. Voc� quer descobrir como os alunos da sua escola se comportam. Ent�o, voc� tem l�, 500 alunos e voc� tem que escolher de maneira aleat�ria um desses 500 alunos. � assim que funciona e � o que n�s chamamos de amostra rand�mica.E, mesmo assim, isso � complicado. Imagine que voc� quer descobrir como os alunos da sua escola funcionam. E voc� quer descobrir qual � o melhor professor da sua escola. Se voc� tem aulas nos turnos da manh�, tarde e noite, s� pegar alunos da manh� pode ser complicado. Ou pegar s� alunos da tarde, ou s� alunos da noite. Porque esse grupo de pessoas pode ter opini�es diferentes, ent�o voc� tem que tomar cuidado com todas essas possibilidades.

Uma outra maneira conhecida pra voc� conseguir a sua amostra � fazer o que n�s chamamos de amostra estratificada. Como assim? Por exemplo, se eu sei que existem grupos. Na minha escola, eu tenho as turmas da manh�, as turmas da tarde e as turmas da noite. A� eu separo manh�, tarde e noite, e dentro desses grupos eu randomizo e pego alguns alunos, pra garantir que eu vou ter sempre alguns alunos de cada turno. Generalizando de novo, imagine que voc� queira descobrir times de futebol do Brasil, s� que voc� s� entrevista pessoas do sudeste pra baixo. A�, obviamente, vai dar S�o Paulo, Corinthians, Gr�mio, Internacional... Mas, ningu�m vai falar que torce pro Sport, por exemplo, porque voc� n�o pegou pessoas do nordeste. Ent�o, se eu fosse fazer uma amostra estratificada no pa�s, eu pegaria um pouquinho de pessoas do sul, um pouquinho do sudeste, um pouquinho do norte, nordeste, centro-oeste. Isso � o que n�s chamamos de amostra estratificada.

De novo: existem t�cnicas diferentes pra voc� buscar por conjuntos de pessoas. Ent�o, eu j� falei pra voc� que voc� tem que selecionar com carinho na hora de selecionar sua amostra. Agora, vamos entender no nosso desenho, no nosso gr�fico, como isso ficaria. Imagine que aqui eu tenha um histograma, lembra do histograma? Ele conta pra mim, mais ou menos, a frequ�ncia pela vari�vel que eu estou medindo, como, por exemplo, a altura da popula��o. Ent�o, aqui eu tenho, nesse eixo (horizontal) a altura, nesse eixo (vertical) a frequ�ncia. Quantas pessoas t�m 1,50m? Quantas t�m 1,60m, 1,70m etc? E a gente sabe que, se a nossa distribui��o for normal, a nossa curva � mais ou menos assim, certo?

<img src="6.png"/>

Imagine que isso (a curva) � a minha popula��o. Quando eu seleciono a minha amostra menorzinha, pronta pra ser estudada, estou imaginando que o histograma dela � mais ou menos assim:

<img src="7.png"/>

Parecido com o da popula��o. Imagine que � uma normal tamb�m, s� que tem menos dados. � essa a diferen�a da popula��o pra amostra, certo? Eu tenho simplesmente menos dados.

Sabendo disso, eu quero agora, ent�o, calcular as coisas para a amostra que � a que cont�m os meus n�meros e generalizar pra popula��o. M�dia, como a gente faz? A m�dia, dado que as distribui��es s�o normais, n�s acreditamos que a m�dia da amostra � igual � m�dia da popula��o. Simples assim, sem segredo. Mas, agora, a pergunta � a vari�ncia. Lembra o que � a vari�ncia? � mais ou menos quando os n�meros est�o espalhados no gr�fico. Nesse caso, como n�s sabemos que a popula��o � muito maior e provavelmente tem aqueles outliners etc, n�s temos uma f�rmula um pouquinho diferente de calcular a vari�ncia.

Vamos l�. Voc� lembra que, para calcular a vari�ncia, eu fazia a diferen�a de cada n�mero para a m�dia e dividia pelo n�mero de elementos? Vai continuar a mesma coisa. Ent�o, eu vou dar o mesmo exemplo da aula passada. Deixa eu ver os n�meros:

1, 2 e 9
M�dia: 4
Ent�o, a nossa f�rmula era assim, certo? A m�dia menos o n�mero, mais a m�dia menos o pr�ximo n�mero, mais a m�dia menos o �ltimo n�mero, dividido pelo n�mero de elementos. (4-1)+(4-2)+(4-9)/3

E a�, n�s t�nhamos aquele problema de que aqui (no �ltimo par�ntese da f�rmula) o n�mero fica negativo, um cancela o outro, e n�s resolv�amos isso elevando o numeral ao quadrado.

(4-1)�+(4-2)�+(4-9)�
At� aqui, sem segredo. A diferen�a � que n�s acrescentamos um "-1"

(4-1)�+(4-2)�+(4-9)�/3-1
Esse "-1" � a diferen�a pra gente calcular a vari�ncia da amostra. Por que -1? � uma conven��o da estat�stica. Eu n�o vou entrar nos detalhes profundos disso, mas, a ideia � a seguinte. Se eu tiro o n�mero 1, o resultado final dessa conta vai ser um n�mero maior, certo? Se eu dividir por 2, o resultado � maior do que se eu dividir por 3. Por que eu fa�o isso? Porque eu sei que a vari�ncia da minha popula��o � maior do que a vari�ncia da minha amostra. Ent�o, � por isso que eu tiro um n�mero aqui (na divis�o), pra que esse n�mero fique um pouquinho maior e a�, por consequ�ncia, mais parecido com o da minha curva azul aqui (imagem I) que � a da popula��o. � isso, basicamente, que muda na hora de tentar generalizar. Fa�o l� a estat�stica descritiva com m�dia, desvio padr�o, vari�ncia etc da amostra pra popula��o. Ent�o, � isso: a m�dia � igual e a vari�ncia voc� acrescenta "-1" na parte de baixo da sua divis�o pra que o n�mero fique maior e provavelmente muito mais parecido com o da popula��o.

Nessa aula, eu discuti com voc�s as amostras, que � um assunto fundamental num trabalho de estat�stica. Idealmente, voc� n�o consegue alcan�ar sua popula��o inteira, voc� precisa selecionar um conjunto de sujeitos, de pessoas ou do que voc� est� fazendo o seu experimento e, idealmente, essa amostra � representativa em rela��o � popula��o. Como aquele exemplo que eu dei pra voc�s do Brasil, se voc� vai ver times de futebol, voc� n�o vai olhar s� o sul e sudeste, voc� tem que conseguir pessoas do Brasil inteiro. N�o vai entrevistar s� as pessoas da sua casa. Se voc� quer descobrir alguma coisa da sua universidade, voc� n�o vai falar s� com os alunos do per�odo da manh�, porque os alunos do per�odo da noite s�o diferentes e fazem parte dessa popula��o. � assim que n�s tentamos fazer estudos sem ter acesso � popula��o, pensando nessa amostra.

<h2>Sobre amostra</h2>
O que � uma amostra?
R:Uma parte significativa e ating�vel da popula��o, que usamos para nossos testes e estudos.


<h2>Divisor da f�rmula</h2>
Porque subtra�mos 1 do divisor na f�rmula da vari�ncia da amostra?
R: Para que o valor da vari�ncia fique maior, e dessa forma, mais parecido com o valor real da popula��o.

<h2>Valor da vari�ncia</h2>
Se a quantidade de elementos na amostra � grande, o que acontece com o valor da vari�ncia?
R: Quanto maior, mais parecido com o valor da vari�ncia da popula��o ela ser�.

---------------------------------------------------------------------------------------------------------------
<h1>Se��o 10 - Praticando: Graus de Liberdade</h1>

Popula��o != Amostra

Amostra � o que temos em m�os quando estudamos

Vari�ncia acreditamos que a vari�ncia da popul��o seja maior que a vari�ncia da amostra. Usamos:n -1

Degrees of Freedom ou Graus de Liberdade

Se a amostra � grande, a vari�ncia da popula��o e da amostra ser�o parecidos.

Graus de Liberdade = Vari�veis que podem ser mudadas a vontade.

Ol�!

Na lousa, eu mostrei pra voc�s a diferen�a de popula��o e amostra. E mostrei que amostra � o que n�s geralmente temos em m�os quando vamos fazer um estudo. E mostrei tamb�m que a f�rmula da vari�ncia, em particular, muda se for pra amostra ou pra popula��o. A gente coloca um n-1 no divisor. E a gente subtrai 1 por qu�? Porque n�s acreditamos que a vari�ncia da popula��o seja maior do que a da amostra. E a� esse -1 faz com que o n�mero fique maior, e a gente acredita que isso � mais pr�ximo da vari�ncia da popula��o. Esse n-1 � o que n�s chamamos, em ingl�s, de degrees of freedom (graus de liberdade). E essa aula em particular eu n�o vou mostrar no R, at� porque n�o tem muita coisa pra mostrar, mas vou mostrar pra voc�s de onde veio esse n-1.

Ent�o, graus de liberdade, degrees of freedom, eu falei pra voc�s que � n-1. Imagine o seguinte exemplo: se eu disser pra voc� que eu tenho quatro n�meros que eu n�o sei quais s�o: x, y, z e t (planilha do excel, respectivamente: A2, B2, C2, D2). S� que eu sei que a soma de x+y+z+t = 10. Aqui o excel n�o faz, obviamente, porque � vari�vel. Mas, eu sei que a soma tem que ser 10. A minha pergunta �, que n�mero eu posso p�r em x? Se s�o quatro n�meros, e x � o primeiro n�mero. Que n�mero eu posso p�r em x? Qualquer um. O n�mero que eu escolher n�o tem problema,se eu escolher 600, eu vou poder ter uma combina��o de outros tr�s n�meros cuja soma vai me dar 10. Vamos supor que o primeiro seja 3 (x=3). O pr�ximo n�mero agora, que n�mero pode ser? Tamb�m qualquer um. O n�mero que eu escolher, eu vou poder dar um jeito de que os pr�ximos dois corrijam pra dar 10. Vamos supor que o pr�ximo seja 2 (y=2). Agora, eu estou no terceiro n�mero. Que n�mero pode ser? Tamb�m qualquer um. Vamos supor que seja 1 (z=1). �timo. Agora, o quarto n�mero, que n�mero pode ser? Aqui, veja que eu n�o tenho escolha. Se eu sei que a soma � 10, pra esse n�mero aqui, dado que os anteriores s�o 3, 2 e 1, esse aqui tem que ser 4. Pra que a soma de A2+B2+C2+D2 seja 10. Veja que, de quatro n�meros, eu tinha tr�s que podia escolher � vontade: isso s�o os graus de liberdade, degrees of freedom. E voc� v� que isso aparece em v�rios momentos da estat�stica.

Na f�rmula da vari�ncia, em particular, vamos entender o que � que acontece com esses graus de liberdade. Porque � isso que a gente est� fazendo, dando um grau de liberdade que � o n-1. A gente tem um grau a menos de liberdade do que a gente usa l� na f�rmula da popula��o. Imagine que a soma eu j� saiba, porque ali na vari�ncia a f�rmula � a soma da diferen�a do n�mero pra m�dia ao quadrado, dividido por n. Ent�o, imagine que eu j� saiba que a soma daquilo � 240. E vamos imaginar que n=4. Se n=4, na f�rmula da popula��o vai ficar 240/4. E na f�rmula da amostra, vai ficar 240/3. D� uma olhada em como ficou: da popula��o � 60, da amostra � 80.

n=4 Popula��o: 240/4 = 60 Amostra: 240/3 = 80

Vamos aumentar esse n�mero para n=8.

*Popula��o: 240/8 = 30
*Amostra: 240/7 = 34,28571429
Se aumentar mais ainda, n=20

*Popula��o: 240/20 = 12
*Amostra:240/19 = 12,6317895
Veja s�, antes era 60 e 80, a diferen�a era grande; 30 e 34. Quando foi pra n=20, ficou 12 e 12,6 j� est� bem perto. Agora, d� uma olhada em n=120

n=120
*Popula��o: 240/120 = 2
*Amostra: 240/119 = 2,016806723
A diferen�a j� caiu pra 01. O que isso quer dizer pra gente? Quer dizer que se a sua amostra tem mais de 120 pessoas eu nem preciso muito mais olhar aquele "-1", porque eu j� estou vendo que os n�meros s�o parecidos.E por qu� eu estou dizendo isso? Eu estou dizendo que dependendo do n�mero de pessoas que voc� tem no seu estudo, de elementos que voc� colheu ali, voc� n�o precisa nem se preocupar em usar o n-1 na f�rmula. Isso porque os dois n�meros ser�o muito parecidos. Ent�o era isso que eu queria mostrar pra voc�s aqui: que tem aquela f�rmula l� da amostra, em que a gente faz o n-1, s� que ela faz sentido quando a sua amostra � muito pequena. Quando a sua amostra � grande, os n�meros ser�o parecidos tanto da f�rmula que voc� usa de maneira normal, pra vari�ncia, quanto da f�rmula que voc� usa pra amostra. E esse n-1 � o que n�s chamamos de graus de liberdade.

E agora voc� entendeu tamb�m, embora eu n�o v� entrar no detalhe matem�tico da coisa, de quando usamos o tempo inteiro... Mas quando algu�m diz que tem 4 graus de liberdade, quer dizer que 4 vari�veis est�o livres, podem ser mudadas � vontade. Foi exemplo que eu dei pra voc�s com o numeral 10 no in�cio. Pensa, nesse nosso �ltimo exemplo, que aquele n-1 � o grau de liberdade pra chegarmos nessa soma de 240. Se eu tenho n-1 graus de liberdade, quer dizer que eu tenho n-1 n�meros que eu posso mudar, e s� o �ltimo tem que ser fixo ali.

� isso que eu queria mostrar na aula, ent�o n�o fique muito preocupado se voc� usar a f�rmula da vari�ncia comum, dependendo do tamanho da sua amostra, porque vai dar mais ou menos na mesma, t� legal?


<h2>F�rmula da Vari�ncia</h2>
Por que a f�rmula da vari�ncia para amostras pode ser "ignorada" quando a amostra � grande?
R: Por que, como usamos n-1 como graus de liberdade, e a f�rmula da vari�ncia usa n, quando o n�mero � grande, o resultado acaba sendo muito parecido. Como visto no v�deo, a partir de 120 amostras, a diferen�a entre um e outro � por volta de 0.1.



---------------------------------------------------------------------------------------------
<h1>Se��o 11 - Diminuindo o erro: Intervalos de Confian�a</h1>

Ao inv�s de falar a certeza da m�dia da amostra.
N�o adianta falar o n�mero fixo.
� necess�rio usar um Intervalo
Chamado como Intervalo de Confian�a. 6 a 8, por exemplo.
E existe um n�vel de confian�a que � em porcentagem. 95%, por exemplo.

Quanto mairo o n�vel de confian�a, maior o intervalo de confian�a.
Por exemplo, a altura dos Brasileiros, se voc� quiser 100% de certeza em um n�vel de confian�a, o intervalo pode ser de 90 cm at� 2,10m. O que adiantou esse grande intervalo?

Geralmente � utilizado 95% em um n�vel de confian�a.

Vamos continuar. Na aula passada, n�s discutimos ent�o sobre amostras. Eu tinha minha popula��o, eu n�o consigo chegar nela inteira, preciso fazer meu estudo na minha amostra. E a� eu mostrei pra voc�s como se calcula m�dia na amostra, como se calcula vari�ncia na amostra etc. S� que a gente tem um problema. N�s t�nhamos aquele gr�fico que era mais ou menos assim: um histograma, e a popula��o era alguma coisa parecida com isso . Era uma curva normal, parecida com uma normal. E a amostra, n�s acreditamos que � alguma coisa muito parecida s� que com menos dados nesse histograma, ent�o � alguma coisa assim :


<img src="8.png"/>
amostra

Imagine que voc� descobriu que a m�dia dessa popula��o � 7. Corrigindo: a m�dia da amostra � 7. E a� eu falei pra voc�s que n�s acreditamos que a m�dia da amostra � a m�dia da popula��o. Mas, imagine que voc� teve acesso � amostra, calculou que foi 7 e a� voc�, por algum motivo, teve acesso � popula��o. E descobriu que a m�dia da popula��o n�o era 7, era 7,3. Teve uma pequena diferen�a. O que faz sentido, porque a amostra n�o � a popula��o inteira, a gente est� tentando estimar.Voc� consegue ver o problema de dizer pra algu�m que a m�dia � 7, sendo que voc� n�o tem essa certeza absoluta? Voc� n�o consegue afirmar, com certeza, que a m�dia � 7. Ent�o, o que a gente faz nesses casos? Nesses casos, para n�o errar t�o feio, a gente prefere dar um intervalo pra essa pessoa. Assim, ao inv�s de falar pra ele que eu tenho certeza que a m�dia dessa popula��o � 7, eu prefiro falar o seguinte. A m�dia dessa popula��o est� entre 6 e 8 e eu tenho por volta de 95% de certeza de que isso � verdade.

Veja que � muito melhor eu acertar a expectativa com o meu usu�rio, com o que eu estou fazendo. � nisso que eu quero chegar, n�o adianta eu falar um n�mero fixo. Porque voc� n�o vai acertar. A gente sabe que, na pr�tica, raramente a m�dia da amostra � id�ntica � m�dia da popula��o. Por isso, a gente usa o que chamamos de intervalo de confian�a. No exemplo, o meu intervalo de confian�a � de 6 a 8. E esse 95% que eu coloquei pra voc�s � o que n�s chamamos de n�vel de confian�a. Obviamente, um est� relacionado ao outro, porque dependendo do n�vel de confian�a que eu quero, eu vou ter um intervalo maior ou menor.

S� que pensar no n�vel de confian�a � complicado. Porque, veja s�, se eu dissesse pra voc� que preciso saber a m�dia dessa popula��o com 100% de certeza. Ou, vamos generalizar mais f�cil ainda: preciso que voc� me fale a m�dia das alturas dos brasileiros com 100% de certeza, voc� n�o pode errar, sua vida depende disso. Se voc� pedisse isso pra mim, eu responderia que o intervalo de confian�a da altura do brasileiro varia entre 90 cm e 2,20m. Com 100% de certeza. Percebe? Se eu coloco o n�vel de confian�a muito alto, o que acontece com o meu intervalo? Ele abre. A �nica maneira de ter 100% de certeza � tendo um intervalo muito grande. S� que adiantou o que essa resposta? Se eu falar pra voc� que a altura do brasileiro varia de 30cm a 2,5m? N�o te contei nada novo.

E a�, tem o lado contr�rio. Se eu quiser falar pra voc� que a altura do brasileiro, a m�dia � entre 1,70m e 1,71m, vou ter que dizer que eu tenho 10% de confian�a, porque � dif�cil falar um n�mero desses. Ent�o, voc� tem que balancear o seu n�vel de confian�a. Geralmente, via de regra, a gente usa 95%. Esse � um n�mero que � bastante aceito por diversas comunidades. Por exemplo, a comunidade de computa��o usa o muito o n�mero 95%. J� a medicina, que � uma coisa mais delicada, n�o pode errar... Imagine que estejam fazendo um estudo com rem�dio, n�o pode errar. O n�vel de confian�a geralmente � 99%.

Como calcular o intervalo de confian�a dada uma distribui��o? Aqui, eu n�o vou entrar na matem�tica da coisa, porque isso come�a a ficar bastante complicado. Eu vou mostrar a teoria em alto n�vel e depois a gente aplica usando o computador. � alguma coisa mais ou menos assim. Eu vou desenhar de novo a nossa normal aqui. Aqui est� a m�dia. E a�, eu tenho os nossos desvios padr�es. N�s sabemos que uma distribui��o tem, geralmente, tr�s desvios padr�es, tanto pra direita quanto pra esquerda.

O que essa galera da estat�stica faz pra calcular esses intervalos de confian�a? Eles conseguem olhar essa curva normal como um c�lculo de probabilidade. Como assim? Imagine que isso (eixo horizontal) � a altura da popula��o brasileira. O cara que est� aqui nesse extremo � algu�m extremamente alto, que tem, por exemplo, 2,30m de altura. Ent�o ele est� bem no extremo. A gente olha pra essa curva e tenta descobrir qual � a probabilidade de eu ter um n�mero aqui (onde est� marcado 2,30m). Eu consigo fazer isso porque eu sei a frequ�ncia de cada uma das alturas das pessoas, ent�o eu consigo tentar calcular a probabilidade desse cara estar aqui (com 2,30m).
<img src="9.png"/>
probabilidade

Quando eu digo que o meu n�vel de confian�a � de 95%, eu estou dizendo que h� 95% de chances de eu ter um n�mero nesse intervalo de 6 a 8. Quando eu falo de 100% de n�vel de confian�a, eu estou dizendo que a chance do n�mero estar dentro dessa curva � 100%, estou olhando pra tudo. Ent�o, se voc� pega 100% de confian�a, geralmente voc� come�a na altura que � 30cm (extrema esquerda do gr�fico) e acaba no 2,30m (extrema direita). O 95% de confian�a � mais ou menos boa parte do nosso gr�fico. At� porque, a gente sabe que, tr�s desvios padr�es para a esquerda e tr�s para a direita, voc� tem a m�dia.Tr�s desvios padr�es pra cada lado d� por volta de 99,7% da distribui��o. Quando a gente fala 95, consideram-se por volta de 2,5 desvios padr�es mais ou menos pra cada lado da distribui��o. Eu n�o vou entrar na matem�tica doida da coisa, porque isso faz todo sentido pra quem � estat�stico, pra quem est� cursando uma gradua��o de estat�stica. Pra n�s que somos pessoas que aplicam estat�stica no dia-a-dia, importa � entender o que � um intervalo de confian�a.

E, retomando, o que � um intervalo de confian�a? Eu tenho um n�vel, o meu n�vel de confian�a � de 95%, e eu quero ter a certeza, eu tenho a certeza, de que a minha m�dia est� entre esse intervalo (de 6 a 8). E essa � a confian�a. Como que eu calculo isso, pra gente agora n�o importa, mas � basicamente probabilidade. Ent�o, � assim que n�s fazemos quando queremos ser claros na hora de explicar a m�dia de uma mostra e tentar generalizar pra popula��o: damos um intervalo de confian�a.

<h2>Intervalo de confian�a</h2>
O que � intervalo de confian�a?
R: � o intervalo estimado de algum par�metro estat�stico, como m�dia. Ou seja, ao inv�s de afirmarmos que a m�dia � "90", dizemos que a m�dia est� entre "88" e "92", com 95% de certeza.

<h2>100% de confian�a?</h2>
Por que n�o podemos ter um n�vel de confian�a de 100%?
R: Porque isso implacaria em termo um intervalo muito aberto.

<h2>10% de confian�a?</h2>
Por que n�o podemos ter um n�vel de confian�a de 10%?
R: Porque ter�amos um intervalo muito fechado, mas provavelmente errado. Por exemplo, poder�amos dizer que a m�dia de altura do brasileiro est� entre 1.78 e 1.79, com 10% de certeza. O intervalo � �timo, mas temos confian�a nesse n�mero.



-----------------------------------------------------------------------------------------------------
<h1>Se��o 12 - Praticando: Intervalos de Confian�a</h1>

Ent�o, na lousa, eu discuti com voc�s intervalos de confian�a. Aqui, eu tenho essa vari�vel lizard, com um monte de n�meros:


> lizard = c(6.2,6.6,7.1,7.4,7.6,7.9,8,8.3,8.4,8.5,8.6,8.8,8.8,9.1,9.2,9.4,9.7,9.9,10.2,10,11.3,11.9)
E eu quero calcular o intervalo de confian�a nessa distribui��o. O R n�o me d� uma fun��o padr�o pra isso. Ent�o, a gambiarra que n�s fazemos � usar um teste de hip�tese que tem isso como sa�da. Aqui eu vou usar o t.test, o teste t de student, que eu vou discutir melhor mais pra frente com voc�s. Se eu fizer aqui o t.test e passar o lizard, veja que ele me d� com 95% de confian�a que o intervalo est� entre 8.29 e 9.49. Ent�o esse � o intervalo de confian�a que eu quero.


> t.test(lizard)

    One Sample t-test
data: lizard
t = 30.4769, df = 23, p-value < 2.2e-16
alternative hypothesis: true mean is not equal to 0
95 percent confidence interval
 8.292017 9.499649
sample estimates
mean of x
 8.895833
E eu posso at� mudar o n�vel de confian�a, n�o precisa ser 95%, pode ser 90. Ent�o, por exemplo, conf. level, como um par�metro da fun��o t.test, 09. E aqui ele me d� um intervalo ainda mais restrito. Ficou 8.39 at� 9.39, muito mais restrito.


> t.test (lizard, conf.level=0.9)

    One Sample t-test
data: lizard
t = 30.4769, df = 23, p-value < 2.2e-16
alternative hypothesis: true mean is not equal to 0
90 percent confidence interval
 8.395575 9.396092
sample estimates
mean of x
 8.95833
� assim que eu calculo intervalos de confian�a usando t.test e ignorando o resto. O t.test eu vou mostrar pra voc�s na pr�xima aula, mas aqui, por enquanto, eu vou usar s� essa sa�da dele. E, com esses n�meros, pessoal, d� pra fazer coisas mais legais. Por exemplo, vou calcular a m�dia dessa distribui��o e vou desenhar um histograma:


>
> media <- mean (lizard)
> hist (lizard)
lizard

Ele me deu um histograma. S� que agora eu quero desenhar coisas nele. Vou fazer assim: abline, plota a m�dia pra mim, v de valor, cor azul, e a grossura da linha 2.


>
> media <- mean (lizard)
> hist (lizard)
> abline(v=media, col="blue", lwd=2)
Olha s�, apareceu uma linha bem na m�dia. D� pra melhorar isso, d� pra, por exemplo, colocar uma linha no primeiro limite l� do meu intervalo de confian�a, 8.39. Eu vou pintar essa linha de vermelho e vou coloc�-la bem grossa:


>
> media <- mean (lizard)
> hist(lizard)
> abline(v=media, col="blue", lwd=2)
> abline(v=8.39, col="red", lwd=4)


Um intervalo est� aqui e outro est� no 9.39:

>
> media <- mean (lizard)
> hist(lizard)
> abline(v=media, col="blue", lwd=2)
> abline(v=8.39, col="red", lwd=4)
> abline(v=9.39, col="red", lwd=4)


Lembra que eu falei naquela aula que quando plotava e salvava imagens em arquivo, que eu podia chamar fun��es embaixo de fun��es? Ent�o, eu chamei o hist e ele desenhou um histograma, a� o abline ficou me desenhando linhas. Ent�o, olha s� que legal. Olha aonde est� a m�dia, que eu sei, e d� uma olhada no intervalo de confian�a. Esse � pra 90%, se eu tivesse pedido pra ele calcular o intervalo de confian�a como 70%, ficaria muito mais apertado, veja, 8,58 - 9,20:

> t.test(lizard, conf.level=0,7)

    One Sample t-test
data: lizard
t = 30.4769, df = 23, p-value < 2.2e-16
alternative hypothesis: true mean is not equal to 0
70 percent confidence interval
 8.586334 9.205333
sample estimates
mean of x
 8.895833
Mas � uma confian�a de 70%, ser� que eu quero, ser� que eu n�o quero? J� discutimos sobre isso. � assim que n�s calculamos, usando a� a gambiarrazinha de usar o teste t de student que d� pra gente como sa�da um intervalo de confian�a.


<h2>Intervalos de confian�a com R</h2>
Qual a fun��o utilizada para calcularmos intervalos de confian�a, j� que o R n�o tem uma nativa?
R: t.test() e olhar para ambos os intervalos impressos

<h2>N�vel de confian�a</h2>
Qual o par�metro informado para t.test, que indica o n�vel de confian�a dsejado?
R: conf.level = 0.8, por exemplo para 80% de n�vel de confian�a.


