# Modern E-Commerce Platform

[English](#english) | [Português](#português)

## English

### Overview
A modern, fully-featured e-commerce platform built with React, featuring a responsive design, shopping cart functionality, product search, and professional UI components. Demonstrates advanced frontend development skills with modern web technologies.

### Features
- **Responsive Design**: Mobile-first approach with Tailwind CSS
- **Product Catalog**: Dynamic product grid with filtering and search
- **Shopping Cart**: Add, remove, and update quantities
- **Modern UI**: Professional components with shadcn/ui
- **Interactive Elements**: Hover effects, animations, and micro-interactions
- **Product Reviews**: Star ratings and customer feedback
- **Category Filtering**: Browse products by category
- **Real-time Search**: Instant product search functionality

### Technologies Used
- **React 18**: Modern React with hooks and functional components
- **React Router**: Client-side routing for SPA navigation
- **Tailwind CSS**: Utility-first CSS framework
- **shadcn/ui**: High-quality UI component library
- **Lucide Icons**: Beautiful, customizable icons
- **Vite**: Fast build tool and development server

### Installation

1. Clone the repository:
```bash
git clone https://github.com/galafis/Modern-E-Commerce-Platform.git
cd Modern-E-Commerce-Platform
```

2. Install dependencies:
```bash
npm install
# or
pnpm install
```

3. Start the development server:
```bash
npm run dev
# or
pnpm run dev
```

4. Open your browser to `http://localhost:5173`

### Usage

#### Main Features
- **Browse Products**: View featured products on the homepage
- **Search**: Use the search bar to find specific products
- **Add to Cart**: Click "Add to Cart" on any product
- **Manage Cart**: View, update quantities, or remove items
- **Category Filter**: Click category badges to filter products

#### Component Structure
```
src/
├── components/
│   └── ui/           # shadcn/ui components
├── assets/           # Static assets
├── App.jsx          # Main application component
├── App.css          # Application styles
└── main.jsx         # Entry point
```

### Key Components

#### Header Component
- Navigation with logo and search
- Shopping cart icon with item count
- User account and wishlist icons

#### ProductCard Component
- Product image with hover effects
- Star ratings and review counts
- Add to cart functionality
- Category badges

#### CartPage Component
- Shopping cart management
- Quantity controls
- Order summary with totals
- Checkout preparation

### Styling Features
- **Responsive Grid**: Adapts to different screen sizes
- **Hover Effects**: Smooth transitions and scaling
- **Modern Cards**: Clean, professional product cards
- **Color Scheme**: Consistent blue and purple gradient theme
- **Typography**: Clear hierarchy with proper font weights

### Mock Data
The application includes sample product data with:
- Electronics (headphones, smartwatch, speaker)
- Fashion (backpack)
- Food (coffee beans)
- Sports (yoga mat)

### Future Enhancements
- User authentication and profiles
- Payment integration (Stripe, PayPal)
- Product reviews and ratings system
- Wishlist functionality
- Order history and tracking
- Admin dashboard for product management

### Contributing
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Português

### Visão Geral
Uma plataforma de e-commerce moderna e completa construída com React, apresentando design responsivo, funcionalidade de carrinho de compras, busca de produtos e componentes de UI profissionais. Demonstra habilidades avançadas de desenvolvimento frontend com tecnologias web modernas.

### Funcionalidades
- **Design Responsivo**: Abordagem mobile-first com Tailwind CSS
- **Catálogo de Produtos**: Grid dinâmico com filtragem e busca
- **Carrinho de Compras**: Adicionar, remover e atualizar quantidades
- **UI Moderna**: Componentes profissionais com shadcn/ui
- **Elementos Interativos**: Efeitos hover, animações e micro-interações
- **Avaliações de Produtos**: Classificações por estrelas e feedback de clientes
- **Filtragem por Categoria**: Navegar produtos por categoria
- **Busca em Tempo Real**: Funcionalidade de busca instantânea de produtos

### Tecnologias Utilizadas
- **React 18**: React moderno com hooks e componentes funcionais
- **React Router**: Roteamento client-side para navegação SPA
- **Tailwind CSS**: Framework CSS utility-first
- **shadcn/ui**: Biblioteca de componentes UI de alta qualidade
- **Lucide Icons**: Ícones bonitos e personalizáveis
- **Vite**: Ferramenta de build rápida e servidor de desenvolvimento

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/galafis/Modern-E-Commerce-Platform.git
cd Modern-E-Commerce-Platform
```

2. Instale as dependências:
```bash
npm install
# ou
pnpm install
```

3. Inicie o servidor de desenvolvimento:
```bash
npm run dev
# ou
pnpm run dev
```

4. Abra seu navegador em `http://localhost:5173`

### Uso

#### Funcionalidades Principais
- **Navegar Produtos**: Visualizar produtos em destaque na página inicial
- **Buscar**: Usar a barra de busca para encontrar produtos específicos
- **Adicionar ao Carrinho**: Clicar em "Add to Cart" em qualquer produto
- **Gerenciar Carrinho**: Visualizar, atualizar quantidades ou remover itens
- **Filtro de Categoria**: Clicar em badges de categoria para filtrar produtos

#### Estrutura de Componentes
```
src/
├── components/
│   └── ui/           # Componentes shadcn/ui
├── assets/           # Assets estáticos
├── App.jsx          # Componente principal da aplicação
├── App.css          # Estilos da aplicação
└── main.jsx         # Ponto de entrada
```

### Componentes Principais

#### Componente Header
- Navegação com logo e busca
- Ícone do carrinho com contagem de itens
- Ícones de conta de usuário e lista de desejos

#### Componente ProductCard
- Imagem do produto com efeitos hover
- Classificações por estrelas e contagem de avaliações
- Funcionalidade adicionar ao carrinho
- Badges de categoria

#### Componente CartPage
- Gerenciamento do carrinho de compras
- Controles de quantidade
- Resumo do pedido com totais
- Preparação para checkout

### Recursos de Estilo
- **Grid Responsivo**: Adapta-se a diferentes tamanhos de tela
- **Efeitos Hover**: Transições suaves e escalonamento
- **Cards Modernos**: Cards de produtos limpos e profissionais
- **Esquema de Cores**: Tema consistente com gradiente azul e roxo
- **Tipografia**: Hierarquia clara com pesos de fonte apropriados

### Dados Mock
A aplicação inclui dados de produtos de exemplo com:
- Eletrônicos (fones de ouvido, smartwatch, speaker)
- Moda (mochila)
- Comida (grãos de café)
- Esportes (tapete de yoga)

### Melhorias Futuras
- Autenticação e perfis de usuário
- Integração de pagamento (Stripe, PayPal)
- Sistema de avaliações e classificações de produtos
- Funcionalidade de lista de desejos
- Histórico de pedidos e rastreamento
- Dashboard administrativo para gerenciamento de produtos

### Contribuindo
1. Faça um fork do repositório
2. Crie uma branch de feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -am 'Adicionar nova feature'`)
4. Push para a branch (`git push origin feature/nova-feature`)
5. Crie um Pull Request

### Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

