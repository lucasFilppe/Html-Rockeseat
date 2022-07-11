# Html-Rockeseat

#BOX MODEL

- Fundamental para fazer layouts na web
- Maior facilidade para aplicar o CSS

## O que é?

Uma caixa retangular que possui propriedades

- Tamanho(largura x altura) = width e height
- Conteúdo = content
- Bordas = border
- Preenchimento interno = padding
- Espaços fora da caixa = margin

### Cada elemento é uma caixa

# display: block vs display: inline

- como as caixas se comportam em relação as outras
- comportamento extenos das caixas

**block**

- Ocupa toda linha, colocando o proximo elemento abaixo desse
- Width e heigth são respeitados
- Padding, margin, border irão funcionar normalmente

**inline**

- Elemento ao lado do outro
- Width e heigth não funcionam
- Padding, margin, border irão funcionar somente os valores horizontais

### Exemplos

- block: p, div, h1...
- inline:a, strong, span...

# Layouts

É a maneira que os elementos estão distribuídos na tela

### Normal Flow

É maneira que os elementos block e inline ficam na página

### Flex box

A caixa se torna flex, fazendo com que os elementos possam receber melhor :

- Alinhamento
- ordenação
- tamanhos flexiveis

### Flex sizing

- Flexivel
- altera width\heigth dos intens para preenchimento de espaços do flex container

### Direção dos itens

- Flex é uma dimensão (horizontal ou vertical)
- Podemos mudar a direção com "flex-direction"
- Valores: (row |row reverse| column | column-reverse)

### Flex-wrap

- Podemos usar multi linhas
- Cada nova linha, um novo flex container
