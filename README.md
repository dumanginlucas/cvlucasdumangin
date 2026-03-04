# Meu Currículo - Portfólio Online

Um portfólio profissional moderno e responsivo construído com **React**, **TypeScript**, **Vite** e **Tailwind CSS**.

## 🚀 Tecnologias Utilizadas

- **React 18** - Biblioteca JavaScript para interfaces de usuário
- **TypeScript** - Tipagem estática para JavaScript
- **Vite** - Build tool rápido e moderno
- **Tailwind CSS 4** - Framework CSS utilitário
- **Radix UI** - Componentes acessíveis e sem estilo
- **Wouter** - Roteador leve para React
- **React Hook Form** - Gerenciamento de formulários
- **Framer Motion** - Animações fluidas
- **Lucide React** - Ícones SVG

## 📋 Pré-requisitos

- **Node.js** 18+ ou superior
- **pnpm** 10+ (recomendado) ou npm/yarn

## 🛠️ Instalação Local

1. **Clone o repositório:**
```bash
git clone <seu-repositorio>
cd meu-curriculo
```

2. **Instale as dependências:**
```bash
pnpm install
```

3. **Inicie o servidor de desenvolvimento:**
```bash
pnpm dev
```

A aplicação estará disponível em `http://localhost:5173`

## 🏗️ Build para Produção

Para criar uma versão otimizada para produção:

```bash
pnpm build
```

Os arquivos compilados estarão na pasta `dist/`.

## 📦 Deploy na Vercel

### Opção 1: Deploy via Git (Recomendado)

1. **Faça push do seu código para o GitHub:**
```bash
git push origin main
```

2. **Acesse [vercel.com](https://vercel.com) e faça login**

3. **Clique em "New Project"**

4. **Selecione seu repositório GitHub**

5. **Configure as variáveis de ambiente (se necessário)**

6. **Clique em "Deploy"**

Pronto! Sua aplicação será automaticamente deployada e atualizada a cada push.

### Opção 2: Deploy via Vercel CLI

1. **Instale a Vercel CLI:**
```bash
npm i -g vercel
```

2. **Execute o deploy:**
```bash
vercel
```

3. **Siga as instruções interativas**

## 📁 Estrutura do Projeto

```
meu-curriculo/
├── client/
│   ├── public/              # Arquivos estáticos
│   ├── src/
│   │   ├── components/      # Componentes React
│   │   ├── pages/          # Páginas da aplicação
│   │   ├── contexts/       # Context API
│   │   ├── hooks/          # Custom hooks
│   │   ├── lib/            # Utilitários
│   │   ├── App.tsx         # Componente principal
│   │   ├── main.tsx        # Entrada da aplicação
│   │   └── index.css       # Estilos globais
│   └── index.html          # HTML principal
├── shared/                  # Código compartilhado
├── package.json            # Dependências do projeto
├── vite.config.ts          # Configuração do Vite
├── tsconfig.json           # Configuração do TypeScript
└── vercel.json             # Configuração da Vercel
```

## 🎨 Personalizando o Tema

O tema pode ser customizado editando as variáveis CSS em `client/src/index.css`:

```css
:root {
  --primary: oklch(0.623 0.214 259.815);
  --background: oklch(1 0 0);
  /* ... outras variáveis */
}
```

## 🔧 Scripts Disponíveis

| Comando | Descrição |
|---------|-----------|
| `pnpm dev` | Inicia o servidor de desenvolvimento |
| `pnpm build` | Cria a versão otimizada para produção |
| `pnpm preview` | Visualiza a versão de produção localmente |
| `pnpm check` | Verifica erros de TypeScript |
| `pnpm format` | Formata o código com Prettier |

## 🌐 Variáveis de Ambiente

Se precisar adicionar variáveis de ambiente, crie um arquivo `.env.local`:

```env
VITE_API_URL=https://api.example.com
VITE_PUBLIC_KEY=sua-chave-publica
```

As variáveis devem começar com `VITE_` para serem acessíveis no cliente.

## 📝 Licença

Este projeto está sob a licença MIT.

## 👤 Autor

**Dumanginadm**

---

**Dúvidas ou sugestões?** Abra uma issue no repositório!
