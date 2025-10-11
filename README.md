This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

## Deploy na Vercel (instruções em português)

Passos mínimos para publicar este projeto na Vercel:

1. Crie uma conta em https://vercel.com e conecte o repositório (GitHub, GitLab ou Bitbucket).
2. Na dashboard do projeto, vá para Settings -> Environment Variables.
	- Adicione a variável `NEXT_PUBLIC_URLAPI` com o valor da sua API (por exemplo: `https://snake-api-cvo1.vercel.app`).
	- Marque como `Environment` desejado (Preview/Production) conforme sua necessidade.
3. A Vercel detecta automaticamente que este é um app Next.js e usará a build padrão.
	- Build command: `npm run build` (já definido em `package.json`).
	- Output directory: não é necessário, Next.js controla isso.
4. Opcional: se quiser usar secrets pela CLI, instale `vercel` e rode:

```bash
# faça login (se necessário)
vercel login
# adicionar secret (substitua o valor)
vercel secret add NEXT_PUBLIC_URLAPI https://snake-api-cvo1.vercel.app
```

5. Depois de configurar as variáveis, acione um deploy (push no branch conectado ou clique em Deploy na dashboard).

Notas:
- Não inclua arquivos `.env` no repositório — a Vercel lê as variáveis do painel de Environment Variables.
- Este repositório inclui um `vercel.json` para guiar a build do Next.js, mas a configuração de variáveis de ambiente/secret deve ser feita no painel da Vercel ou via CLI conforme preferir.

