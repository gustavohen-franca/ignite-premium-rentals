# Ignite Premium Rentals

Aplicação web de aluguel de carros esportivos premium construída com Vite + React + TypeScript, Tailwind CSS, shadcn/ui (Radix), React Router, React Query, Firebase (Auth/Firestore), Vitest + RTL e Husky + lint-staged.

## Tecnologias

- Vite, React 18, TypeScript
- Tailwind CSS, shadcn/ui (Radix)
- React Router DOM
- TanStack React Query
- Firebase (Auth, Firestore)
- Zod para validação
- Vitest + React Testing Library
- ESLint + Prettier + Husky + lint-staged

## Configuração de ambiente

Crie um arquivo `.env.local` na raiz com as chaves do Firebase:

```
VITE_FIREBASE_API_KEY=
VITE_FIREBASE_AUTH_DOMAIN=
VITE_FIREBASE_PROJECT_ID=
VITE_FIREBASE_STORAGE_BUCKET=
VITE_FIREBASE_MESSAGING_SENDER_ID=
VITE_FIREBASE_APP_ID=
```

## Scripts

- `npm run dev` – Inicia o servidor de desenvolvimento
- `npm run build` – Build de produção
- `npm run preview` – Preview do build
- `npm run lint` – Lint do projeto
- `npm run lint:fix` – Lint com correção
- `npm run format` – Formata com Prettier
- `npm run format:check` – Verifica formatação
- `npm run typecheck` – Checagem de tipos
- `npm test` – Testes (Vitest)

## Husky + lint-staged

Inicialize o Husky (uma vez por repositório):

```bash
npx husky install
```

Pre-commit executa Prettier, ESLint (com fix) e testes afetados.

## Rotas principais

- `/` (Home)
- `/catalog` (Catálogo)
- `/cars/:id` (Detalhes)
- `/checkout` (Checkout, pagamento fictício)
- `/login` (Login com Google)
- `/signup` (Cadastro simulado)
- `/account` (Dashboard do usuário)

## Desenvolvimento

1. Instale dependências: `npm install`
2. Configure `.env.local`
3. Inicialize Husky: `npx husky install`
4. Rode: `npm run dev`

## Estrutura

- `src/components/` – Componentes UI
- `src/pages/` – Páginas/rotas
- `src/hooks/` – Hooks
- `src/lib/` – Integrações (ex.: Firebase, API)
- `src/types/` – Tipos e schemas Zod

## Licença

Copyright © Ignite Premium Rentals
