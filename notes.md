# Projeto Mídia social

- Criar as camandas utilizando a tag <span>.

- Transformação 2D ou 3D de um elemento.

- Transições CSS

- Opacidade / tranparência do CSS

- Hover

- nth-child ()

##  Tag <span>

A tag <span> é um contêiner embutido usado para marcar uma parte de um texto ou uma parte de um documento. 

É facilamente estilizada por CSS ou manipulada com JavaScript usando o atributo class ou id.

É muito parecida com o elemento <div>, mas <div> é um elemento de nível de bloco e <span> é um elemento inline. 

## Propriedade de tranformação CSS

A  propriedade transform aplica uma transformação 2D ou 3D a um elemento. Esta propriedade permite girar, dimensionar, mover, inclina, etc., elementos.

- Rotate: Rotaciona o elemento para esquerda e direita conforme o valor em deg (grau celsius), sendo que número possito rotaciona para direita e númerp negativa rotaciona para esquerda.

transform: rotate(20deg);

- Rotate x e y: Rotaciona o elemento no eixo vertical (y) e horizontal (x) também utilizando o valor deg (grau celsius). 

transform: rotatex(20deg);

transform: rotateY(45deg);

- Skew: O método inclina um elemento ao longo dos eixos X e Y  pelo ângulos fornecidos. O exemplo a seguir inclina o elemento <div> 20 graus ao longo do eixo X e 10 graus ao longo do eixo Y: 

transform: skew(20deg, 10deg);

- SkewX: O método inclina um elemento ao longo do eixo x pelo ângulo dado. O exemplo a seguir inclina o elemento <div> 20 graus ao longo do eixo X: 

transform: skewX(20deg);

- SkewY: O método inclina um elemento ao longo do eixo Y pelo ângulo dado. O exemplo a seguir inclina o elemento <div> 20 graus ao longo do eixo Y:

transform: skewY(20deg);

-  Translate: O método translate move um elemento de sua posição atual de acordo com o parâmetros fornecidos para o eixo X e o Y. O exemplo a seguir move o elemnto <div> 5 pixels para a direita e 100 pixels para baixo de sua posição atual:
   
transform: translate(50px, 100px);

- Scale: O método aumenta ou diminui o tamanho de um elemento de acordo com os parâmetros fornecidos para largura e altura. O exemplo a seguir aumenta o elemento para duas vezes sua largura original e três vezes sua altura original: 

transform: scale(0.5, 0.5);


    