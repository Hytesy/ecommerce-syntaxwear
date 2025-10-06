# SyntaxWear - E-commerce de Tênis e Sneakers

## Descrição

SyntaxWear é um projeto de e-commerce focado na venda de tênis e sneakers. A interface foi desenvolvida para ser moderna, atraente e responsiva, proporcionando uma excelente experiência de usuário em diversos dispositivos.

## Funcionalidades

- **Design Responsivo:** A interface se adapta a diferentes tamanhos de tela, como desktops, tablets e smartphones.
- **Navegação Intuitiva:** Menus e links bem estruturados para facilitar a navegação do usuário.
- **Seções de Destaque:** Áreas dedicadas para destacar produtos e categorias especiais.
- **Estrutura Modular:** O código é organizado em componentes, facilitando a manutenção e a escalabilidade.

## Tecnologias Utilizadas

- **HTML5:** Para a estruturação do conteúdo da página.
- **CSS3:** Para a estilização e o design da interface, utilizando variáveis para facilitar a customização.

## Estrutura do Projeto

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
│       ├── product-categorie.css
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

## Como Utilizar

Para visualizar o projeto, basta abrir o arquivo `index.html` em seu navegador de preferência.

```bash
# Exemplo de como abrir no Google Chrome (Windows)
start chrome index.html
```

## Customização

O projeto foi desenvolvido com foco na facilidade de customização.

### Cores e Fontes

As cores principais e a fonte padrão podem ser facilmente alteradas no arquivo `css/variables.css`.

```css
/* css/variables.css */
:root {
    --fonte-principal: 'Ubuntu', sans-serif;
    /* Adicione ou altere as variáveis de cor aqui */
}
```

### Imagens

Todas as imagens do projeto estão localizadas na pasta `images/`. Para alterar as imagens, substitua os arquivos existentes mantendo os mesmos nomes, ou atualize os caminhos nos arquivos CSS e HTML correspondentes.

- **Banners:** `images/banners/`
- **Ícones:** `images/icons/`
- **Logotipo:** `images/logo/`
- **Produtos:** `images/products/`
