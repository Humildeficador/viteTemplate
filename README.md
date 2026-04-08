# Vite Template

Um template minimalista e robusto para iniciar projetos Vite.

## 🚀 Tecnologias

- [Vite](https://vitejs.dev/)
- [React](https://react.dev/) + [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS v4](https://tailwindcss.com/)
- [Biome](https://biomejs.dev/) (Linting & Formatação)
- [PNPM](https://pnpm.io/) (Gerenciador de Pacotes)

## ⚙️ Pré-requisitos

Antes de começar, você vai precisar ter instalado:

- [Node.js](https://nodejs.org/) (versão 18 ou superior)
- [PNPM](https://pnpm.io/installation)

Se você ainda não tem o PNPM, instale-o via terminal:

```bash
npm i -g pnpm
```

## 📦 Instalação

Clone o repositório e instale as dependências:

1. Clone o projeto:

   ```bash
   git clone https://github.com/Humildeficador/viteTemplate.git
   ```

2. Entre no diretório:

   ```bash
   cd viteTemplate
   ```

3. Instale as dependências (estritamente com pnpm):

   ```bash
   pnpm install
   ```

## 💻 Desenvolvimento

Para rodar o aplicativo em modo de desenvolvimento com Hot Module Replacement (HMR):

   ```bash
   pnpm dev
   ```

## 🛠️ Build (Produção)

Para compilar os arquivos para produção:

   ```bash
   pnpm build
   ```

Para testar o build de produção localmente:

   ```bash
   pnpm preview
   ```

## 🧹 Linting e Formatação

Para formatar e procurar por erros no código (usando o Biome), rode:

   ```bash
   pnpm lint
   ```
