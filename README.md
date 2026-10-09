# Portfólio — Chris

Site estático de portfólio para UX/UI e Product Design.  
Inclui integração com Vercel Speed Insights para monitoramento de performance.

## 🚀 Desenvolvimento

O projeto agora utiliza Vite para bundling e inclui Vercel Speed Insights.

### Instalação

```bash
npm install
```

### Desenvolvimento local

```bash
npm run dev
```

### Build para produção

```bash
npm run build
```

O build gera os arquivos otimizados na pasta `dist/`.

### Preview do build

```bash
npm run preview
```

## Personalização

- Atualize nome, apresentação, projetos e links em `index.html`.
- Troque o e-mail de exemplo `seuemail@exemplo.com` pelo contato profissional.
- Ajuste cores, tipografia e layout em `styles.css`.

## 📦 Deploy na Vercel

Importe este repositório em [vercel.com/new](https://vercel.com/new). Configure o projeto com:

- **Build Command:** `npm run build`
- **Output Directory:** `dist`

A Vercel executará o build automaticamente e o Speed Insights começará a coletar métricas de performance após o deploy.
