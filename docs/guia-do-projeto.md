# 🛍️ SintaxWear - Documentação e Guia do Projeto

Bem-vindo à documentação do projeto **SintaxWear**!

---

## 📁 Estrutura de Pastas e Arquivos

Aqui está a explicação simplificada de como o projeto está organizado:

```text
├── index.html                  # Página principal da loja
├── /css/
│   ├── base.css                # Reset CSS, variáveis de cores/fontes (Design Tokens) e utilitários
│   ├── layout.css              # Estrutura geral da página (containers, alinhamentos e grids gerais)
│   └── /components/            # Estilos separados para cada bloco da interface:
│       ├── header.css          # Barra superior e menu de navegação
│       ├── panel.css           # Barra de avisos / ofertas no topo
│       ├── hero.css            # Banner principal de destaque
│       ├── product-card.css    # Card individual de produto
│       ├── product-grid.css    # Grade/vitrine de produtos
│       ├── newsletter.css      # Caixa de cadastro para novidades
│       └── footer.css          # Rodapé com informações institucionais
├── /images/
│   ├── /logo/                  # Logotipos da marca
│   ├── /banners/               # Banners para o carrossel/hero
│   └── /products/              # Fotos dos produtos (subpastas por categoria)
├── /icons/                     # Ícones em formato SVG
├── /fonts/                     # Arquivos de fontes locais (caso necessário)
├── /favicons/                  # Ícones para a aba do navegador
└── /docs/                      # Documentações, briefings e anotações
```

---

## 🚀 Próximos Passos Sugeridos
1. **Adicionar novos produtos**: Duplicar a estrutura do `.product-card` no [index.html](file:///C:/Users/Leonardo%20Lorca%20%28JG%29/Music/0%20DEV-2.0/08-DEV-2.0-e-commerce-projeto/ecommerce-sintaxwear/index.html) para exibir mais itens.
2. **Imagens reais**: Adicionar as imagens do projeto dentro das respectivas pastas em `/images/`.
3. **Interatividade / JavaScript**: Adicionar carrinho de compras dinâmico ou filtros de produtos se desejar.
