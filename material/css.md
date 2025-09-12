1. Sintaxe Básica do CSS
A sintaxe é a forma como o código CSS é escrito. É composta por três partes principais:

Seletor: O que você quer estilizar (ex: h1, p, .minha-classe).

Propriedade: O aspecto que você quer mudar (ex: color, font-size, margin).

Valor: A definição da propriedade (ex: red, 16px, 20px).

Um exemplo de regra CSS:

CSS

p {
  color: blue;
  font-size: 18px;
}

2. Formas de Adicionar CSS
Existem três maneiras de aplicar estilos a um documento HTML:

Inline: Usando o atributo style diretamente na tag HTML. (Não recomendado)

Interno: Usando a tag <style> dentro do <head> do HTML.

Externo: Criando um arquivo .css e linkando-o no HTML com a tag <link>. (A forma mais usada e recomendada)

3. Seletores
Dominar os seletores é crucial para estilizar elementos específicos.

Seletores de Tipo: Estiliza todas as tags de um tipo (ex: p, h1).

Seletores de Classe: Estiliza elementos com um atributo class específico (ex: .minha-classe).

Seletores de ID: Estiliza um único elemento com um id específico (ex: #meu-id).

Seletores de Atributo: Estiliza elementos com base em seus atributos (ex: [type="text"]).

Pseudo-classes: Estiliza elementos em um estado específico (ex: :hover para quando o mouse está sobre o elemento, :focus para quando o elemento está selecionado).

Seletores Combinadores: Permitem selecionar elementos com base em sua relação com outros (ex: p a para links dentro de parágrafos).

4. Modelo de Caixa (Box Model)
O modelo de caixa é a base de todo layout em CSS. Todo elemento é tratado como uma caixa retangular com as seguintes propriedades:

Content (Conteúdo): Onde o texto e as imagens ficam.

Padding (Preenchimento): O espaço entre o conteúdo e a borda.

Border (Borda): A linha que envolve o preenchimento e o conteúdo.

Margin (Margem): O espaço fora da borda, usado para separar um elemento do outro.

5. Propriedades Essenciais
Cores: color (texto) e background-color (fundo).

Fontes: font-family, font-size, font-weight, font-style.

Layout: display (flexbox, grid, block, inline), position (static, relative, absolute, fixed, sticky).

Dimensionamento: width, height, max-width, min-height.

Centralização: Usar margin: 0 auto; para centralizar elementos de bloco e Flexbox para centralizar em ambos os eixos.

6. Flexbox e Grid
Esses são os dois sistemas de layout mais modernos e poderosos em CSS.

Flexbox (Flexible Box): Perfeito para layouts de uma dimensão (linhas ou colunas). É ideal para alinhar itens em barras de navegação ou formulários.

Grid (CSS Grid Layout): Ideal para layouts de duas dimensões (linhas e colunas). É a escolha perfeita para criar a estrutura geral de uma página.

7. Responsividade
É a capacidade de um site se adaptar a diferentes tamanhos de tela (computador, tablet, celular).

Media Queries: Regras CSS que se aplicam apenas se uma condição for verdadeira (ex: o tamanho da tela for menor que 768px).

Unidades Relativas: Usar unidades como %, em, rem e vw/vh para que o layout se ajuste dinamicamente ao invés de usar valores fixos em px.
