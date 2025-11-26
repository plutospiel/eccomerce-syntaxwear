# SyntaxWear - E-commerce de Tênis e Sneakers

![SyntaxWear](./images/logo/logo.svg)

## 📋 Sobre o Projeto

SyntaxWear é um e-commerce moderno e responsivo especializado na venda de tênis e sneakers online. O projeto apresenta uma interface elegante e intuitiva, com foco em experiência do usuário e design contemporâneo.

## 🚀 Tecnologias Utilizadas

- **HTML5** - Marcação semântica
- **CSS3** - Estilização e layout responsivo
- **Metodologia BEM** - Organização de CSS
- **CSS Variables** - Padronização de cores e estilos
- **Flexbox & Grid** - Layout moderno e responsivo

## 📁 Estrutura do Projeto

```
eccomerce-syntaxwear/
│
├── index.html                 # Página principal
│
├── css/
│   ├── reset.css             # Reset CSS (Andy Bell)
│   ├── base.css              # Estilos base e utilitários
│   └── componentes/
│       ├── variables.css     # Variáveis CSS
│       ├── header.css        # Estilos do cabeçalho
│       ├── hero.css          # Seção hero/banner
│       ├── product-category.css  # Categorias de produtos
│       ├── product-grid.css  # Grid de produtos
│       ├── footer.css        # Rodapé
│       └── newsletter.css    # Newsletter
│
├── images/
│   ├── logo/                 # Logo da marca
│   ├── banners/              # Imagens de banner
│   ├── products/             # Fotos dos produtos
│   └── icons/                # Ícones do site
│
├── fonts/                    # Fontes customizadas
├── favicon/                  # Favicons
└── docs/                     # Documentação adicional
```

## ✨ Funcionalidades

### Header
- Logo da marca
- Menu de navegação principal (Masculino, Feminino, Outlet)
- Menu secundário (Nossas lojas, Sobre)
- Ícones de acesso rápido (Perfil, Ajuda, Carrinho)
- Menu hamburguer para dispositivos móveis

### Seção Hero
- Banner principal com imagem de destaque
- Título e subtítulo promocional
- Botões de call-to-action (Ver Modelos, Comprar)

### Categorias
- Cards de categorias visuais:
  - Casual
  - Esporte
  - Moderno
  - Futurista

### Grid de Produtos
- Layout em grid responsivo
- Card destaque "Krypton One"
- Galeria de produtos com imagens

### Footer
- Formulário de newsletter
- Links para redes sociais (Instagram, WhatsApp, TikTok, Facebook)
- Menu de navegação completo
- Informações de copyright

## 🎨 Padrões de Design

### Cores Principais
- **Primary Purple**: `#6329A2`
- **Dark Gray**: `#333333`
- **White**: `#ffffff`
- **Light Gray**: `#ededed`

### Tipografia
- Fonte principal definida em variáveis CSS
- Tamanhos em `rem` para melhor acessibilidade

### Botões
- `.btn-outline` - Botão com borda branca
- `.btn-filled` - Botão preenchido branco com texto roxo
- Estados de hover com transições suaves

## 📱 Responsividade

O projeto é totalmente responsivo com breakpoints para:
- Desktop (1360px max-width)
- Tablet (1280px e abaixo)
- Mobile (com menu hamburguer)

## 🔧 Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/plutospiel/eccomerce-syntaxwear.git
```

2. Navegue até a pasta do projeto:
```bash
cd eccomerce-syntaxwear
```

3. Abra o arquivo `index.html` em seu navegador ou use um servidor local:
```bash
# Exemplo com Live Server (VS Code)
# Ou Python
python -m http.server 8000
```

## 📦 Recursos do Projeto

### Imagens de Produtos
O projeto inclui imagens de diversos modelos de tênis:
- Tênis casual
- Tênis esportivo
- Tênis moderno
- Tênis futurista
- Modelos masculinos e femininos

### Ícones
- User (Perfil)
- Help (Ajuda)
- Bag (Carrinho)
- Redes sociais (Instagram, WhatsApp, TikTok, Facebook)
- Menu hamburguer

## 🎯 Funcionalidades Planejadas

- [ ] Sistema de carrinho de compras
- [ ] Página de detalhes do produto
- [ ] Filtros de busca avançados
- [ ] Sistema de avaliações
- [ ] Integração com pagamento
- [ ] Área do cliente
- [ ] Sistema de favoritos

## 📝 Metodologia CSS

O projeto utiliza uma arquitetura CSS modular:
- **reset.css**: Normalização de estilos
- **variables.css**: Centralização de variáveis
- **base.css**: Estilos globais e utilitários
- **Componentes**: Cada seção tem seu próprio arquivo CSS

### Unidades de Medida
- Uso de `rem` para tamanhos de fonte e espaçamentos
- Valores em `px` apenas para bordas e detalhes específicos
- `max-width` definido em pixels para containers

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:
1. Fazer um fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abrir um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT.

## 👤 Autor

**plutospiel**
- GitHub: [@plutospiel](https://github.com/plutospiel)

## 🌟 Agradecimentos

- Design inspirado em e-commerces modernos de sneakers
- Reset CSS por Andy Bell
- Comunidade DevQuest

---

**SyntaxWear** - Transforme qualquer passo em presença 👟✨