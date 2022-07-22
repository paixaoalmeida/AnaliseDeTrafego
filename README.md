<HTML>
<BODY>

<div align="center">
  <img src="https://user-images.githubusercontent.com/85945510/179628167-79ee6ed8-06b6-4bd1-bd56-422951d93423.jpeg" width="500">
</div>

<h1> Fundamentos de redes para análise de tráfego </h1>

<h2> Alguns conceitos básicos de Modelo OSI,TCP/IP e pacotes </h2>
<p> Na área de Tecnologia, um dos requisitos básicos para se tornar um <strong> bom </strong> profissional é ter conhecimento a par de <strong> Redes de computadores, </strong> tendo essa matéria consolidada na cabeça, o indivíduo será capaz de entender a lógica por de baixo dos panos das comunicações, obviamente, há muito mais do que apenas isso, mas esse é o pontapé inicial para os estudos em Tecnologia. </p>
<br>

<h2> O quê vai estar disponível aqui? </h2>
<p> Logo abaixo, haverá díversos objetos de estudos da minha própria autoria sobre estudos de <strong> Redes de computadores. </strong> </p>
<p> Isso inclui: <strong> Protocolos, Modelo OSI, TCP/IP, arquiteturas etc. </strong> </p>
<p> Ou seja, uma parte do que é necessário para se dizer que tem conhecimento "básico". </p>
<br>

<h1> Materiais de referência para os estudos </h1>
<a href="https://1drv.ms/u/s!AlVcFaTu7VS23gk2ZLQRGPPz5rTH?e=C9lMuC" target="_blank"> PDFs sobre Redes de computadores</a> 
<br>
<a href="https://pastebin.com/uKu0T47x" target="_blank"> Cursos em vídeo sobre Redes de computadores</a>

<p> Esses links serão atualizados e logo serão adicionados novos materiais.
<br>
<br>

<h1> Como funciona o Modelo OSI e o TCP/IP? </h1>
<p> Ambos são modelos criados para padronizar a forma de funcionamento das redes de computadores, tanto para profissionais de redes e fabricantes de dispositivos de infraestrutura, para explicar na prática, o modelo OSI é teórico e o modelo TCP/IP é um modelo prático, mas ambos tem basicamente a mesma proposta: <b> padronizar a maneira de como os pacotes viajam pela rede até o seu computador. </b>
<br>
<p> Preste atenção na imagem abaixo:

<div align="center">
  <img src="https://user-images.githubusercontent.com/85945510/179632864-5132f1d0-d0a5-4b88-af84-2127dadad53e.jpeg">
</div>

<br>

<p> O modelo OSI é constituido de 7 camadas, já o modelo TCP/IP é constituido de 4, pois nele a camada de <b> aplicação </b> se junta com a de <b> apresentação e sessão </b> e as camadas <b> física e de enlace </b> se juntam em uma só, formando a camada de <b> host e rede. </b>

<br>

<p> Uma boa parte das pessoas por algum motivo pensa que o "flow" da camda é de baixo para cima, coisa que é falsa, a não ser no processo de <b> desencapsulamento </b> de pacotes, que nós iremos ver mais tarde. 
<p> Basicamente, a pilha funciona de baixo para cima, sendo que há uma camada abstraida que seria a do <b> aplicativo/programa </b> que está gerando os dados na rede. 

<br><br>

<div>
  <h1> Qual a função de cada camada? </h1>
  <p> <b> Camada de aplicação: </b> A camada de aplicação é uma camada considerada de alto nível, nela habitam os <b>protocolos</b>. O aplicativo manda uma mensagem e nessa camada são decididos qual será a porta de destino do dado (de acordo com o protocolo) e qual é a função da mensagem. Nessa camada,os dados ainda são apenas mensagens sendo transmitidas, a parte em que esses dados viram pacotes ainda é mais embaixo, mais especificamente na camada de <b>transporte.</b><br>
  <p> <b>Camada de apresentação</b>: A camada de apresentação faz jus ao seu nome, ela define o formato do dado e também o converte de uma maneira que possa ser entendido pelas outras camadas. Essa camada basicamente atua como um tradudor dos dados para a rede, processos como criptografia, compressão de dados, você provavelmente entendeu, ela formata toda a informação no modo que o receptor irá entender, ou que a transmissão tenha designado.
  <h1> EM PROGRESSO... </h1>

</BODY>
</HTML>
