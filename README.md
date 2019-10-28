# FlexBox - CSS 3
Repositório utilizado para o aprendizado do FlexBox do CSS3.


##### DISPLAY:FLEX
Torna o elemento que o utiliza um container e os filhos do container flex-itens.

##### FLEX-DIRECTION
Define a direção que o conteúdo dentro do container flex estará alinhado.
- column: Funciona como coluna.
- column-reverse: Funciona como coluna e deixa os itens no final da coluna, em baixo.
- row: Funciona como linha.
- row-reverse: Funciona como linha e deixa os itens no final da mesma, à direita.

##### ALIGN-ITENS:
Alinha no eixo contrário do flex-direction, ou seja, se o mesmo estiver column, ele alinhará horizontalmente (em linha) e se tiver como row ele alinhará verticalmente (em coluna). 
- center: Alinha no centro.
- flex-end: Alinha no final do eixo.
- flex-start: Alinha no início do eixo.

##### JUSTIFY-CONTENT:
Alinha no eixo do flex-direction, ou seja, se tiver em coluna alinhará em coluna, se tiver em linha, alinhará em linha. 
- center: Alinha no centro.
- flex-end: Alinha no final do eixo.
- flex-start: Alinha no início do eixo.
- space-around: Alinha ao centro com espaços em volta das bordas.
- space-beetween: Alinha ao centro com espaços entre os itens, sem borda (margin).
- space-evenly: Alinha mais ao centro com espaços.

##### FLEX-WRAP:WRAP
Ele ocupa o espaço dos itens enquanto tiver espaço naquela linha. Ou seja, se tivermos 3 itens de 150px e uma largura de 340px, ele irá deixar dois elementos na primeira linha e irá pular o terceiro elemento para a segunda, já que: 150 + 150 = 300px. Além disso também temos o wrap-reverse.

##### ALIGNT-CONTENT: 
Alinha os elementos quando eles estão em mais de uma linha, ou seja, ele funciona somente com o flex-wrap:wrap. Tendo as mesmas possibilidades do justify-content. Mas fazendo na horizontal.

### ITENS UTILIZADOS NOS FILHOS:

##### FLEX-GROW
Mantém os itens ocupando toda a largura disponível em tela, ou seja, se um item tem uma largura menor do que a tela, ele irá aumentá-lo para preencher a tela toda.
- 1: Flex grow funcionando.
- 0: Flex grow desativado.

##### FLEX-SHRINK
Mantém os itens "espremidos" dentro do container, ou seja, um item que tenha largura maior que da viewport e do container, irá diminuir para caber na tela, sem criar um overflow.
- 1: Flex shrink funcionando.
- 0: Flex shring desativado. Ele irá criar um overflow.

##### FLEX
Soma do Flex-Grow com o Flex-Shrink. Se quisermos que o elemento aumente se necessário mas não se esprema, colocamos algo como "Flex: 1 0"


##### ORDER
Alinha os itens ordenando de acordo com o que você define, em valores numéricos começando do 0. Isso serve para quando temos que ordenar os itens do flex por algum motivo em um ambiente responsivo.

