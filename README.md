# 👟 SintaxWear - E-commerce de Tênis & Sneakers

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Design Responsivo](https://img.shields.io/badge/Design-Responsivo-success?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Concluído-blue?style=for-the-badge)

> Projeto desenvolvido durante o curso **DEV 2.0**. Uma landing page e storefront moderna, visualmente atraente e 100% responsiva para uma loja virtual de sneakers e calçados urbanos.

---

## 📌 Sumário

- [Sobre o Projeto](#-sobre-o-projeto)
- [Funcionalidades](#-funcionalidades)
- [Layout e Seções](#-layout-e-seções)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Como Executar o Projeto](#-como-executar-o-projeto)
- [Boas Práticas Aplicadas](#-boas-práticas-aplicadas)
- [Possíveis Melhorias Futuras](#-possíveis-melhorias-futuras)
- [Autor](#-autor)

---

## 📖 Sobre o Projeto

A **SintaxWear** é uma interface de e-commerce focada na experiência do usuário para venda de tênis e sneakers exclusivos. O objetivo do projeto foi construir uma página web do zero utilizando **HTML5 Semântico** e **CSS3 Moderno**, aplicando conceitos de arquitetura modular de estilos, Flexbox, CSS Grid e design responsivo (adaptável a smartphones, tablets e desktops) sem depender de frameworks externos.

---

## ✨ Funcionalidades

- 📱 **Menu Mobile Off-Canvas / Hambúrguer**: Menu lateral retrátil criado exclusivamente com CSS (*Checkbox Hack*), sem necessidade de JavaScript inicial.
- 🎯 **Banner Hero Impactante**: Apresentação de produto principal com chamadas para ação (*Call to Action - CTA*).
- 🏷️ **Categorias Rápidas**: Acesso facilitado às linhas de tênis (*Casual*, *Esporte*, *Moderno*, *Futurista*) com efeitos de sobreposição visual (*overlay*).
- 🧱 **Vitrine Assimétrica em CSS Grid**: Exibição moderna de produtos utilizando `grid-template-areas`.
- 📬 **Inscrição de Newsletter**: Seção para captura de e-mails de clientes no rodapé.
- 🌐 **Links e Navegação Institucional**: Estrutura de rodapé completa com navegação por categorias e links para redes sociais.

---

## 🖥️ Layout e Seções

O site está estruturado nas seguintes seções:

1. **Header Fixo (Navegação)**:
   - Logotipo da marca vetorizado em SVG.
   - Menu central com categorias de vestuário e calçados.
   - Ícones de acesso rápido: Lojas, Sobre, Minha Conta, Ajuda e Carrinho de Compras.
   - Menu hambúrguer adaptativo para telas menores que `1280px`.

2. **Seção Hero (Destaque Principal)**:
   - Chamada do modelo "Krypton One".
   - Imagem de fundo responsiva com versão dedicada para desktop e mobile (`hero.jpg` e `hero-mobile.jpg`).
   - Botões interativos estilizados com transição de hover.

3. **Seção de Categorias**:
   - Cards com imagens de fundo representativas para cada estilo de sneaker.
   - Botões centralizados sobre uma camada semitransparente.

4. **Grid de Produtos (Destaque)**:
   - Grade em CSS Grid de 4 colunas (adaptada para 2 colunas em telas menores que `768px`).
   - Card principal de chamada ("Krypton One - Estilo urbano com atitude").
   - Imagens de modelos e variações de cores dos sneakers.

5. **Rodapé (Footer)**:
   - Campo de captura para newsletter.
   - Ícones de redes sociais (Instagram, WhatsApp, TikTok, Facebook).
   - Mapa de links do site e créditos de direitos autorais.

---

## 🛠️ Tecnologias Utilizadas

- **[HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML)**: Estruturação semântica da página (`<header>`, `<main>`, `<section>`, `<nav>`, `<footer>`, etc.), garantindo melhor acessibilidade e SEO.
- **[CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS)**:
  - **CSS Reset**: Baseado no Modern CSS Reset de Andy Bell para consistência entre navegadores.
  - **Variáveis CSS (Custom Properties)**: Centralização de fontes e configurações globais no `:root`.
  - **Flexbox**: Alinhamento e distribuição dos elementos do cabeçalho, botões e rodapé.
  - **CSS Grid (`grid-template-areas`)**: Criação da vitrine assimétrica na seção de produtos.
  - **Media Queries**: Responsividade completa para larguras de `1280px`, `1000px`, `768px` e `500px`.
  - **Tipografia**: Integração com a fonte **Ubuntu** via Google Fonts.
- **SVG & JPG Otimizados**: Ícones vetoriais leves e imagens de alta qualidade.

---

## 📂 Estrutura do Projeto

A organização dos arquivos segue uma arquitetura limpa e modular:

```text
ecommerce-sintaxwear/
├── css/
│   ├── components/                 # Estilos específicos de cada componente da página
│   │   ├── footer.css              # Estilos do rodapé, formulário de newsletter e redes
│   │   ├── header.css              # Estilos do cabeçalho, logo e menu hambúrguer
│   │   ├── hero.css                # Estilos da seção banner principal (Hero)
│   │   ├── product-category.css    # Estilos dos cards de categorias
│   │   └── product-grid.css        # Estilos da grade assimétrica de produtos (CSS Grid)
│   ├── base.css                    # Estilos globais (body, botões gerais, container main)
│   ├── reset.css                   # Reset de estilos padrão dos navegadores
│   └── variables.css               # Declaração de fontes e variáveis CSS globais
│
├── images/
│   ├── banners/                    # Imagens de fundo do Hero (desktop e mobile)
│   ├── favicons/                   # Ícones de favoritos da aba do navegador
│   ├── icons/                      # Ícones em formato SVG (carrinho, usuário, redes, etc.)
│   ├── logo/                       # Logotipo oficial da SintaxWear em SVG
│   └── products/                   # Fotos dos produtos e calçados em destaque
│
├── index.html                      # Documento principal da aplicação web
└── README.md                       # Documentação completa do projeto
```

---

## 🚀 Como Executar o Projeto

Como este é um projeto construído com tecnologias web nativas (HTML e CSS), você não precisa instalar nenhuma biblioteca ou servidor complexo para executá-lo.

### Método 1: Abrir diretamente no Navegador

1. Baixe ou clone o repositório em seu computador:
   ```bash
   git clone https://github.com/SEU_USUARIO/ecommerce-sintaxwear.git
   ```
2. Navegue até a pasta do projeto.
3. Dê dois cliques no arquivo `index.html` (ou clique com o botão direito e selecione **Abrir com** > seu navegador preferido: Chrome, Edge, Firefox, etc.).

### Método 2: Utilizando a extensão Live Server no VS Code (Recomendado)

1. Abra a pasta do projeto no [Visual Studio Code](https://code.visualstudio.com/).
2. Instale a extensão **Live Server** (caso ainda não a tenha).
3. Clique com o botão direito no arquivo `index.html` e selecione **"Open with Live Server"** (ou use o atalho `Alt + L, Alt + O`).
4. O navegador abrirá automaticamente com recarregamento em tempo real a cada alteração salva.

---

## 💡 Boas Práticas Aplicadas

- **Arquitetura CSS Componentizada**: Em vez de ter um único arquivo CSS gigante, cada seção possui seu próprio arquivo `.css` na pasta `components/`, tornando a manutenção mais simples e organizada.
- **Acessibilidade (a11y)**: Uso de atributos como `aria-label` e textos alternativos (`alt`) em imagens e ícones para facilitar o uso por leitores de tela.
- **Transições Suaves**: Uso de `transition` no CSS para efeitos de hover suaves em links e botões.
- **Otimização para Dispositivos Móveis**: Ajuste de tamanhos de fontes, espaçamentos e layouts para diferentes tamanhos de tela.

---

## 🔮 Possíveis Melhorias Futuras

- [ ] Adicionar **JavaScript** para gerenciar um carrinho de compras funcional (adicionar/remover itens e calcular total).
- [ ] Implementar páginas de detalhes dos produtos (`produto.html`), categorias e página de checkout.
- [ ] Validação interativa de e-mail no formulário de newsletter.
- [ ] Implementação de carrossel de imagens com suporte a toque (*touch swipe*) no mobile.
- [ ] Modo escuro (*Dark Mode*) com chaveamento via CSS / JS.

---

## 👨‍💻 Autor

Desenvolvido por **Leonardo Lorca** como parte dos estudos no curso **DEV 2.0**.

---
*Gostou do projeto? Sinta-se à vontade para deixar uma estrela ⭐️ no repositório!*