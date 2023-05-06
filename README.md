# Jquery_estudo
Pequeno projeto feito no estudo sobre JQuery.

  Este projeto consiste num pequeno jogo de palavras.
  Inicialmente, a página index apresenta o jogo, ao clicar em jogar,
o usuário é redirecionado a página do jogo, na qual ele escolhe 
palavras aleatórias que vêm do diretório servidor, num arquivo
chamado "frases.js", uma API que contém as frases.
  Em seguida, o usuário digita a frase escrita, e conforme ele acerta
 as palavras, a text-area permanece verde, se errar, ela fica vermelha
 a contar um tempo que se esgota. Por fim, ao esgotar o tempo, aparece
 num placar que fica salvo através do método POST do ajax na API placar.js,
 também do diretório servidor.
 
  Neste projeto utilizei as tecnologias do JQuery e Ajax, além de alguns frameworks
e plugins utéis com o uso do JQuery na estilização, como Materialize para ícones,
Slider na implementação de CSS, Selectize na na seção e cadastro de jogadores no placar
e Tootilpster como notificação estilizada.
