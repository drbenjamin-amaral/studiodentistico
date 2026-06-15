# Studio Dentístico — Landing Page

Landing page da mentoria **Studio Dentístico**, do Dr. Benjamin Amaral.

Site estático (HTML/CSS/JS), pronto para deploy na Vercel.

## Estrutura

```
studio-dentistico/
├── index.html              # Página principal
├── assets/
│   └── images/             # Imagens e logotipo
├── vercel.json             # Configuração Vercel
├── .gitignore
└── README.md
```

## Deploy no GitHub + Vercel

### 1. Subir no GitHub

Na pasta do projeto:

```bash
git init
git add .
git commit -m "Landing page Studio Dentístico"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/studio-dentistico.git
git push -u origin main
```

> Crie o repositório vazio no GitHub antes do `git push` (sem README, sem .gitignore).

### 2. Publicar na Vercel

1. Acesse [vercel.com](https://vercel.com) e faça login com sua conta GitHub
2. Clique em **Add New → Project**
3. Importe o repositório `studio-dentistico`
4. A Vercel detecta o site estático automaticamente — não precisa alterar nada
5. Clique em **Deploy**

O site ficará online em uma URL como `studio-dentistico.vercel.app`. Você pode configurar um domínio próprio nas configurações do projeto.

### Deploy manual (sem GitHub)

Se preferir subir direto pela Vercel CLI:

```bash
npm i -g vercel
vercel
```

## Atualizações futuras

Depois de conectado ao GitHub, cada `git push` na branch `main` gera um novo deploy automaticamente na Vercel.

## Contato WhatsApp

Todos os botões apontam para: `https://wa.me/5512992186532`
