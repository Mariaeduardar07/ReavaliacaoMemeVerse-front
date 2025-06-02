# MemeVerse 🚀

Uma plataforma moderna de compartilhamento de memes desenvolvida com Next.js 15, focada em componentização e reutilização de código.

## 📋 Sobre o Projeto

O MemeVerse é uma aplicação web voltada para adolescentes e jovens adultos compartilharem e descobrirem memes. O projeto foi desenvolvido com foco em:

- **Componentização**: Arquitetura modular com componentes reutilizáveis
- **Props**: Gerenciamento eficiente de dados entre componentes
- **CSS Modules**: Estilização isolada e responsiva
- **UX/UI**: Interface intuitiva e responsiva

## 🚀 Tecnologias Utilizadas

- **Next.js 15** - Framework React de produção
- **React 18** - Biblioteca para construção de interfaces
- **CSS Modules** - Estilização com escopo isolado
- **JavaScript ES6+** - Linguagem de programação moderna

## 📦 Instalação e Execução

### Pré-requisitos

- Node.js (versão 18 ou superior)
- npm ou yarn

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/Mariaeduardar07/ReavaliacaoMemeVerse-front.git
cd memeverse
```

2. Instale as dependências:
```bash
npm install
```

3. Execute o projeto em modo de desenvolvimento:
```bash
npm run dev
# ou
yarn dev
```

4. Acesse a aplicação em: `http://localhost:3000`

## 🏗️ Estrutura de pasta

```
src/
├── app/
│   ├── favicon.ico
│   ├── globals.css
│   ├── layout.jsx
│   ├── page.jsx
│   └── page.module.css
└── components/
    ├── Header/
    │   ├── Header.jsx
    │   └── Header.module.css
    ├── HeroSection/
    │   ├── HeroSection.jsx
    │   └── HeroSection.module.css
    ├── MemeCard/
    │   ├── MemeCard.jsx
    │   └── MemeCard.module.css
    ├── InteractionBar/
    │   ├── InteractionBar.jsx
    │   └── InteractionBar.module.css
    ├── CategoriesSection/
    │   ├── CategoriesSection.jsx
    │   └── CategoriesSection.module.css
    ├── Sidebar/
    │   ├── Sidebar.jsx
    │   └── Sidebar.module.css
    ├── FeaturedMemesSection/
    │   ├── index.jsx
    │   └── featuredMemesSection.module.css
    ├── FeaturedMemeCard.jsx
    ├── CreatorsSection/
    │   ├── index.jsx
    │   └── creatorsSection.module.css
    ├── NewsletterSection/
    │   ├── index.jsx
    │   └── newsletterSection.module.css
    └── Footer/
        ├── Footer.jsx
        └── Footer.
```

## 🧩 Componentes Implementados

- **Header:** Barra superior de navegação do site.
- **HeroSection:** Seção principal de destaque com o meme do dia.
- **MemeCard:** Card individual para exibição de memes no feed.
- **InteractionBar:** Barra de interações (curtir, comentar, compartilhar) dos memes.
- **CategoriesSection:** Seção de categorias de memes.
- **Sidebar:** Barra lateral com eventos, premium e tags.
- **Footer:** Rodapé da aplicação.
- **FeaturedMemesSection:** Seção de memes em destaque.
- **CreatorsSection:** Seção de criadores em destaque.
- **NewsletterSection:** Seção para inscrição na newsletter.

---

## 🔧 Desafios Enfrentados e Soluções

- **Dificuldades em props:** Tive dificuldades para passar e utilizar props entre os componentes, principalmente no início do projeto.
- **Bastantes erros durante o processo, mas consegui resolver:** Enfrentei vários erros de sintaxe, importação e estrutura, mas consegui solucionar identificando o erro

---

## 📱 Responsividade

A aplicação foi desenvolvida com abordagem mobile-first, garantindo:

- **Mobile (< 768px):** Layout em coluna única, navegação hamburger, componentes empilhados verticalmente.
- **Tablet (768px - 1023px):** Layout em duas colunas, navegação simplificada, sidebar adaptada.
- **Desktop (≥ 1024px):** Layout completo com sidebar fixa, navegação completa e distribuição de conteúdo em múltiplas colunas.

---

## 👨‍💻 Desenvolvedor

Desenvolvido por Maria Eduarda como parte do curso de desenvolvimento de sistema.