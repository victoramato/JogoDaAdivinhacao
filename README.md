<h1> Jogo de Adivinhação </h1>

<h2> Descrição do Projeto </h2>

**Instruções do jogo:**

O programa gera sempre um novo número aleatório, no limite de 0 a 100, que o usuário deve adivinhar em, no máximo, 5 tentativas.

O jogo guia o usuário para que ele saiba se o número inserido por ele é maior ou menor que o número a ser descoberto.

Caso o usuário não adivinhe em até 5 tentativas, ele perde o jogo e tem a possibilidade de re-executar o código novamente para jogar e tentar adivinhar o novo número sorteado pelo algoritmo.

Não se esqueça de inserir "OK" para começar o jogo (do contrário, ele não valida e inicia).

___

**Explicação do código:**

Para capturar as entradas do usuário, foi usada a classe Scanner.

O jogo está programado dentro de um laço do-while e, para ser inicializado, necessita de uma confirmação do usuário por meio da entrada "OK" (que independe de estar escrito com capslock).
Enquanto o usuário não inserir a palavra "ok", o jogo não é iniciado.

Os números aleatórios são gerados pela classe "Random" numa faixa de 0 a 100.

As tentativas do jogador são contabilizadas por meio de um laço for.

O laço for contém condicionais if-else que avaliarão o número inserido pelo jogador, exibirão uma mensagem personalizada dependendo da entrada do usuário e 
contabilizarão a quantidade de tentativas restantes do usuário.

Caso o usuário chegue a 0 tentativas sem acertar o número sorteado pelo algoritmo, o programa exibe uma mensagem de que o usuário perdeu o jogo e o número sorteado pelo algoritmo naquele jogo.

___

<h2> Habilidades adquiridas: </h2>

Esse projeto foi feito quando eu ainda estava aprendendo a aprender linguagens; ou seja, quando ainda estava no começo da minha jornada como programador back-end. Dessa forma, para não parecer redundante as informações colocadas nos tópicos dessa apresentação, listei no tópico "Habilidades requisitadas" não só as habilidadess necessárias para programar esse projeto, mas também as adquiridas por mim nesse processo (que são exatamente as mesmas).

<h2> Habilidades requisitadas: </h2>

Para (re)criar esse projeto você necessitará consolidar e aplicar certos conhecimentos específicos:

1. Declaração de variáveis e tipos primitivos (tipos utilizados: int e double)
2. Estruturas de repetição (estruturas utilizadas: do-while)
3. Estruturas condicionais (estruturas utilizadas: if-else)
4. Operadores de igualdade (operadores utilizados: == e !=)
5. Operadores relacionais (operadores utilizados: >, < e >=)
6. Operadores de atribuição composta (operadores utilizados: += e -=)
7. Operador de decremento (operador utilizado: -- (pós-decremento));
8. Declaração de Strings
9. Conferência da entrada do "tipo" String do usuário com a entrada solicitada pelo programa (variavel.equalsIgnoreCase())
10. Importação e aplicação da classe Scanner de acordo com os tipos primitivos e a classe String
11. Importação e aplicação da classe Random

<h2> Linguagens Utilizadas: </h2>

- <b> Java 17 </b> 

<h2> Ambiente utilizado: </h2>

- <b> Windows 11 </b>
- <b> IntelliJ IDEA </b>

<h2> Ilustrações do programa: </h2>

<p align="center">
Tela inicial do jogo: <br/> <br/>
<img src="https://imgur.com/vwL7bxr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
Validação do usuário:  <br/> <br/>
<img src="https://imgur.com/VtjUHVM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
Mensagem do prompt caso o usuário perca o jogo: <br/> <br/>
<img src="https://imgur.com/J6HfrDv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
Mensagem do prompt caso o usuário ganhe o jogo:  <br/> <br/>
<img src="https://imgur.com/y4F6BRm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
_______

<p align = "center">
<i> Gostaria de agradecer à escola de programação Alura por ter esse projeto em meio ao seu material didático. Sem ele, eu não teria aprendido tanto e muito menos feito esse projeto tão rico para quem está iniciando sua carreira no mundo da tecnologia. </i> </p>

      Muito obrigado por acompanhar a leitura dessa apresentação até aqui! Desfrute-o como quiser! 😁☕
