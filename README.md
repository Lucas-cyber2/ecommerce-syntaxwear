# SyntaxWear - Tênis e Sneakers Online

Este é o repositório do site da SyntaxWear, uma landing page para uma loja online de tênis e sneakers. O projeto foi desenvolvido como uma página estática utilizando HTML semântico e CSS moderno, com uma estrutura de arquivos bem organizada.

## 🚀 Sobre o Projeto

A SyntaxWear é uma marca fictícia de calçados com foco em estilos que variam do casual e esportivo ao moderno e futurista. Esta landing page serve como a principal vitrine online da marca, apresentando os modelos em destaque, categorias de produtos e informações institucionais.

## ✨ Funcionalidades

- **Design Responsivo:** A interface se adapta a diferentes tamanhos de tela, de dispositivos móveis a desktops.
- **Navegação Intuitiva:** Um cabeçalho fixo com links para as principais categorias e um menu de acesso rápido.
- **Seções Principais:**
    - **Hero Banner:** Uma seção de grande impacto visual para destacar o principal lançamento.
    - **Categorias de Produtos:** Cards que direcionam para as seções de calçados (Casual, Esporte, Moderno, Futurista).
    - **Grade de Produtos:** Uma vitrine com os tênis em destaque e os modelos mais populares.
- **Rodapé Completo:** Inclui um formulário de inscrição para newsletter, links para redes sociais e um mapa do site.

## 📁 Estrutura de Arquivos

O projeto está organizado da seguinte forma para garantir manutenibilidade e clareza:

```
ecommerce-syntaxwear/
├── index.html              # Arquivo principal da página
├── README.md               # Este arquivo
└── assets/                 # Contém todos os recursos visuais e de estilo
    ├── css/                # Arquivos de folha de estilo
    │   ├── base.css        # Estilos base (body, fontes, etc.)
    │   ├── reset.css       # Reset de estilos padrão dos navegadores
    │   ├── variables.css   # Definição de variáveis CSS (cores, fontes)
    │   └── components/     # Estilos para componentes específicos da UI
    │       ├── footer.css
    │       ├── header.css
    │       ├── hero.css
    │       ├── product-category.css
    │       └── product-grid.css
    └── img/                # Contém todas as imagens e ícones
        ├── banners/
        ├── favicons/
        ├── icons/
        ├── logo/
        └── products/
```

### CSS
A arquitetura do CSS é modular e baseada em componentes.
- **`reset.css`**: Remove os estilos padrão do navegador para garantir consistência.
- **`variables.css`**: Centraliza as variáveis do projeto (cores, tamanhos de fonte, etc.), facilitando a manutenção do design system.
- **`base.css`**: Aplica estilos globais ao corpo do documento.
- **`components/`**: Cada arquivo nesta pasta estiliza um componente específico da página (cabeçalho, rodapé, etc.), tornando o código mais fácil de entender e gerenciar.

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Para a estrutura e semântica do conteúdo.
- **CSS3:** Para a estilização, layout (Flexbox/Grid) e responsividade.

## ⚡ Como Executar

Este é um projeto puramente front-end e não requer um servidor ou processo de build. Para visualizá-lo:

1. Clone este repositório:
   ```sh
   git clone https://github.com/Lucas-cyber2/ecommerce-syntaxwear.git
   ```
2. Navegue até a pasta do projeto.
3. Abra o arquivo `index.html` diretamente no seu navegador de preferência.

E pronto! A página será carregada.
