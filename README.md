# Novo GameStore Angular

E-commerce completo de jogos desenvolvido com Angular 18 e Node.js, otimizado para deploy no Vercel.

## Sobre o Projeto

Aplicação de e-commerce para o projeto caixaverso da parceria CAIXA+ADA. 

##  Funcionalidades

### Frontend (Angular 18)
-  **Página Inicial** - Showcase dos jogos em destaque
-  **Catálogo de Produtos** - Listagem completa de jogos
-  **Detalhes do Produto** - Informações detalhadas de cada jogo
-  **Carrinho de Compras** - Gerenciamento de itens
-  **Resumo do Pedido** - Finalização de compras
-  **Internacionalização** - Suporte a múltiplos idiomas (PT/EN)
-  **Design Responsivo** - Otimizado para todos os dispositivos

### Backend (Node.js + Express)
-  **Autenticação JWT** - Sistema de login seguro
-  **API RESTful** - Endpoints para produtos e pedidos
-  **Prisma ORM** - Gerenciamento de banco de dados
-  **Upload de Arquivos** - Gerenciamento de imagens
-  **Middleware de Segurança** - Proteção de rotas

## 🛠️ Tecnologias Utilizadas

### Frontend
- **Angular 18** - Framework principal
- **Angular Material** - Componentes UI
- **ngx-translate** - Internacionalização
- **RxJS** - Programação reativa
- **TypeScript** - Linguagem de programação

### Backend
- **Node.js** - Runtime JavaScript
- **Express.js** - Framework web
- **Prisma** - ORM para banco de dados
- **JWT** - Autenticação
- **bcryptjs** - Criptografia de senhas
- **Multer** - Upload de arquivos



## 📁 Estrutura do Projeto

```
novo-gamestore-angular/
├── 📁 frontend/          # Aplicação Angular
│   ├── 📁 src/
│   │   ├── 📁 app/       # Componentes e páginas
│   │   ├── 📁 assets/    # Recursos estáticos
│   │   └── 📄 index.html
│   ├── 📄 angular.json
│   └── 📄 package.json
├── 📁 api/              # Backend Node.js
│   ├── 📁 src/          # Código fonte da API
│   ├── 📁 prisma/       # Schema e migrações
│   ├── 📄 index.js      # Serverless function
│   └── 📄 package.json
├── 📄 vercel.json       # Configuração do Vercel
├── 📄 .vercelignore     # Arquivos ignorados no deploy
├── 📄 package.json      # Scripts do monorepo
└── 📄 README.md
```



### 1. Clone o repositório
```bash
git clone https://github.com/hebrones/novo-gamestore-angular.git
cd novo-gamestore-angular
```

### 2. Instale as dependências
```bash
# Instalar dependências de todo o projeto
npm run install:all
```

### 3. Configuração do ambiente
```bash
# Configure as variáveis de ambiente na pasta api
cp api/.env.example api/.env
```

### 4. Execute o projeto

#### Desenvolvimento (Frontend + API)
```bash
npm run dev
```

#### Apenas Frontend
```bash
npm run dev:frontend
# ou
cd frontend && npm start
```

#### Apenas API
```bash
npm run dev:api
# ou
cd api && npm run dev
```

-  Framework: Angular
-  Build Command: `npm run build`
-  Output Directory: `frontend/dist/app`
-  API Routes: `/api/*`

### 3. Variáveis de ambiente
Configure no painel do Vercel:
```
DATABASE_URL=sua_url_do_banco
JWT_SECRET=seu_jwt_secret
```

## 📱 Funcionalidades Implementadas

###  Concluídas
- [x] Estrutura base do projeto
- [x] Componentes de UI responsivos
- [x] Sistema de roteamento
- [x] Carrinho de compras funcional
- [x] Internacionalização (PT/EN)
- [x] Integração com API
- [x] Configuração do Vercel
- [x] Botão "Finalizar Pedido"


##  Internacionalização

Suporte completo a múltiplos idiomas:
- 🇧🇷 **Português** - Idioma padrão
- 🇺🇸 **English** - Tradução completa


##  Autor

**hebrones**
- GitHub: [@hebrones](https://github.com/hebrones)
- Repositório: [novo-gamestore-angular](https://github.com/hebrones/novo-gamestore-angular)

---

⭐ **Se este projeto foi útil para você, considere dar uma estrela no repositório!**
