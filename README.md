# O que aprendemos 

Este projeto de estudos visa desenvolver as habilidades no uso das propriedades CSS para Flexbox e Grid.

### O que é um flex-container;

Flex container é o elemento que recebe grande parte das propriedades de posicionamento para suas tags filhas;
As limitações de trabalhar com flexbox;
- A principal delas é trabalhar com dois eixos ao mesmo tempo, eixo vertical e horizontal.

### As propriedades de posicionamento justify-content e align-items;

**`justify-content`** distribui o espaço restante do flex container entre suas tags filhas e **`align-items`** alinha verticalmente as tags filhas, ou seja, são propriedades de posicionamento horizontal e vertical respectivamente.

### Trabalhando com Grid

O funcionamento básico do grid;
- A ideia de grid container é bem parecida com flex container, mas no grid container o fluxo é vertical e também ganhamos acesso a outras propriedades.

Propriedades para criar linhas e colunas: grid-template-rows e grid-template-columns;

- Os valores que essas propriedades recebem são os tamanhos das colunas/linhas. Ex: para 3 colunas de 30px a propriedade se escreve: grid-template-columns: 30px 30px 30px.

Nova unidade de medida fr;
- É a unidade de medida para trabalhar com proporções de uma maneira mais simples do que porcentagem. Principalmente quando a porcentagem é uma dízima periódica.

Mescla de linhas e colunas com as propriedades grid-columns: span n e grid-rows: span n;

- É o conceito de “mescla de células”. Serve para dizer quantas colunas/linhas um elemento ocupa dentro do grid container.

As propriedades column-gap, row-gap e gap;

- São as propriedades que dão espaçamento entre os grid items.

Como utilizar o valor auto para tamanho de colunas;

- Nem sempre queremos colocar um valor fixo para as colunas/linhas. O valor auto permite que elas se adaptem de acordo com o conteúdo.

Planejar o uso de grid no desenvolvimento;
- Uma técnica muito interessante é usar alguma ferramenta de desenho e esboçar possíveis linhas e colunas em cima do layout recebido.

## Para saber mais

- [FlexBox Froggy](https://flexboxfroggy.com/)

- [A complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

<hr/>
<hr/>
<br/>
<br/>
<br/>

# Guia de estilos

Toda a estilização que será usada no projeto dentro do figma.

[Link do projeto no figma](https://www.figma.com/file/ibWktwVpnog76rMYOdVhks/Dispondo-elementos-com-flexbox-e-grid?node-id=54%3A2358)

## Fonte

```html
Open Sans:
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap">
```

## Cores

corpo: `#1D232A`

cabeçalho: `#1D232A`

cabeçalho mobile: `#15191C`

menu lateral: `#15191C`

cartão: `#2C343A`

fonte: `#FFFFFF`

fonte alternativa: `#95999C`

links: `#0480DC`

botão: `#0480DC`

sombras: `0px 4px 4px rgba(0, 0, 0, 0.16)`

## Ícones

Estão dentro do arquivo de fonte `icones.ttf`. Para usar, primeiro importe a fonte no projeto usando `@font-face` e depois utilize os códigos abaixo para exibir o ícone.

```css
@font-face {
    font-family: 'icones';
    src: url(../font/icones.ttf);
}
```

> Cuidado com a localização do arquivo `icones.ttf`

Camisas = `\e900`

Carrinho = `\e901`

Inicio = `\e902`

Integrantes = `\e903`

Menu = `\e904`

Moeda = `\e905`

Notificação = `\e906`

Pico = `\e908`

Picos = `\e909`

Pinturas = `\e90a`

Play = `\e90b`

Relogio = `\e90c`

Seta-baixo = `\e90d`

Videos = `\e90e`

Visualizacao = `\e90f`

## Espaçamentos

Espaço interno botão: `8px`

Espaço entre elementos do botão: `8px`

Espaço entre elementos: `16px/8px`

Espaçamento interno do corpo: `16px`

Espaçamento entre o título do cartão de recentes e seus itens: `24px`

## Tamanhos

Tamanho do dispositivo mobile: `360px`

Tamanho do dispositivo desktop: `1440px`

Largura máxima do conteúdo principal: `1120px`

Largura máxima de um cartão desktop: `256px`

Altura mínima de um cartão: `320px`