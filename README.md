# galeria_fotos_gatos # :smiley_cat:	


1. HTML Estrutura:

- O documento HTML começa com as tags html, head, e body.
- Na head, são definidos metadados como o conjunto de caracteres e a escala inicial.
- O título da página é definido como "Photo Gallery".
- Um link é incluído para um arquivo de estilo externo chamado "styles.css", que será usado para estilizar a página.

2. Cabeçalho:

- Um elemento header é criado com a classe "header".
- Um título h1 com o texto "css flexbox photo gallery" é inserido dentro do cabeçalho.
- O cabeçalho tem um fundo escuro, texto branco e uma borda inferior laranja.

3. Galeria de Fotos:

- Um elemento div com a classe "gallery" é criado para conter as imagens da galeria.
- Várias tags img são usadas para exibir as imagens da galeria. Cada imagem tem um atributo src que aponta para uma imagem específica na web.

4. CSS Estilos:

- O código CSS começa com a seleção universal *, que define box-sizing como "border-box" para todas as caixas HTML.
- O fundo da página (body) é definido como uma cor de fundo cinza claro.
- O cabeçalho recebe estilos de formatação, como texto centralizado, texto em caixa alta, padding, fundo azul escuro, cor do texto branca e uma borda inferior laranja.
- A classe "gallery" define a formatação da grade da galeria. Ela usa flexbox (display: flex) para organizar as imagens em uma linha flexível.
- As imagens dentro da galeria (gallery img) têm uma largura máxima de 350 pixels, uma altura fixa de 300 pixels, e são redimensionadas para preencher a caixa (object-fit: cover) para que todas as imagens tenham o mesmo tamanho.
Um gap de 16 pixels é adicionado entre as imagens, e a largura máxima da galeria é definida como 1400 pixels.
- A classe "gallery::after" é usada para criar um espaço em branco após a última imagem.


:grinning: No geral, este código cria uma página de galeria de fotos com um cabeçalho atraente e utiliza flexbox para organizar as imagens em uma grade responsiva. As imagens são redimensionadas para manter uma altura consistente e se encaixar dentro das caixas da grade. O resultado final será uma galeria de fotos que se ajusta bem a diferentes tamanhos de tela.
