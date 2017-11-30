# Testes

- Como são realizados os testes em C.A.R.D.S.:

Esse sistema usa um esquema de dificuldade exponencial. Todas as ações tomadas pelos personagens caem dentro de uma categoria de dificuldade entre **trivial** até **impossivel**. Cada dificuldade possui um valor relacionado a ela, no qual o jogador tem que superar para conseguir realizar a ação em questão. Mais sobre as dificuldades, como também exemplos de cada categoria estão em outro arquivo.

Todas as ações tem um atributo relacionado a elas. Levantar um peso, por exemplo, vai requerir força, enquanto lançar uma bola de fogo vai requerir primordial. O rank desse atributo representa quantas cartas o jogador pode jogar no maximo. Para consigar passar no teste, o jogador tem que usar suas cartas para passar o valor da dificuldade, alterada por qualquer modificador valido. Mais sobre os valores de cada carta e os bonus por conjuntos de cartas que são possiveis a serem escritos.

- Tipos de testes:

 