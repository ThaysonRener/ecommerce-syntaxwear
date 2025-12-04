# SyntaxWear

O SyntaxWear é um e-commerce de tênis e sneakers, desenvolvido como parte do curso "Projetos Reais em Dobro" da Dev em Dobro.

## Descrição

Este projeto consiste em uma landing page para uma loja online de calçados, com foco em um design moderno e atraente. A página é totalmente responsiva e apresenta diversas seções, como:

*   **Header:** Com o logo da marca, menu de navegação principal (Masculino, Feminino, Outlet), e um menu de acesso rápido (Nossas lojas, Sobre, Minha conta, Ajuda, Carrinho).
*   **Hero Section:** Uma seção de destaque com uma imagem de fundo, um título chamativo e botões de ação ("Ver modelos" e "Comprar").
*   **Categorias de Produtos:** Cards que direcionam para as diferentes categorias de tênis (Casual, Esporte, Moderno, Futurista).
*   **Grid de Produtos:** Uma grade de imagens que mostra diversos modelos de tênis em destaque.
*   **Footer:** Com um formulário de inscrição para newsletter, links para redes sociais, e um mapa do site com diversas categorias e links úteis.

## Tecnologias Utilizadas

*   **HTML5:** Para a estruturação do conteúdo da página.
*   **CSS3:** Para a estilização e o design do site, utilizando variáveis, Flexbox e Grid Layout para criar um layout responsivo e moderno.
*   **Figma:** O design do site foi baseado em um protótipo criado no Figma.

## Estrutura de Arquivos

O projeto está organizado da seguinte forma:

```
/
├── css/
│   ├── base.css
│   ├── reset.css
│   ├── variables.css
│   └── components/
│       ├── footer.css
│       ├── header.css
│       ├── hero.css
│       ├── product-category.css
│       └── product-grid.css
├── images/
│   ├── banners/
│   ├── favicons/
│   ├── icons/
│   ├── logo/
│   └── products/
├── index.html
└── README.md
```

*   **css/:** Contém todos os arquivos de estilo do projeto.
    *   `base.css`: Estilos básicos do corpo da página, como fontes e cores.
    *   `reset.css`: Reseta os estilos padrão do navegador para garantir uma aparência consistente.
    *   `variables.css`: Define as variáveis de cores e outras propriedades reutilizáveis.
    *   `components/`: Contém os arquivos de estilo para cada componente da página (header, footer, etc.).
*   **images/:** Armazena todas as imagens utilizadas no site, organizadas em subpastas por categoria.
*   **index.html:** É o arquivo principal que estrutura todo o conteúdo da página.
*   **README.md:** Fornece informações detalhadas sobre o projeto.

## Como Utilizar

Para visualizar o site, basta clonar este repositório e abrir o arquivo `index.html` em seu navegador de preferência.

```bash
git clone https://github.com/thaysonrener/ecommerce-syntaxwear.git
cd ecommerce-syntaxwear
# Abra o arquivo index.html no navegador
```
