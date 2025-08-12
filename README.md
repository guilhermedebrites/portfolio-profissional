# Portfólio Profissional

Nesse projeto você conseguirá ver com mais detalhes minhas experiências, skills, projetos ja desenvolvidos e ainda conhecer um pouco mais sobre mim. 

---

## 🔗 Site publicado na nuvem
**Acesse:** https://seu-projeto.vercel.app  

---

## 🧰 Tecnologias utilizadas

- **React** (SPA, UI)
- **TypeScript** (tipagem estática)
- **Vite** (build/dev server rápido)
- **React Router DOM** (rotas)
- **Axios** (HTTP client)

---

## 📦 Dependências

### Produção
- `react`, `react-dom`
- `react-router-dom`
- `axios`
- `zustand`
- `clsx` (utilitário de classes, opcional)

### Desenvolvimento
- `vite` / `@vitejs/plugin-react`
- `typescript`
- `eslint`, `@typescript-eslint/eslint-plugin`, `@typescript-eslint/parser`
- `prettier`, `eslint-config-prettier`, `eslint-plugin-import`

---

## 🗂️ Estrutura de diretórios

```
.
├── public/
│   └── favicon.svg
├── src/
│   ├── assets/           # imagens, ícones, fontes
│   ├── components/       # componentes reutilizáveis
│   ├── hooks/            # hooks personalizados
│   ├── pages/            # páginas (rotas)
│   ├── routes/           # configuração de rotas
│   ├── services/         # clients (ex: axios) e APIs
│   ├── store/            # estado global (zustand)
│   ├── styles/           # estilos globais (ex: tailwind.css)
│   ├── types/            # tipos TypeScript compartilhados
│   ├── utils/            # helpers/formatadores
│   ├── App.tsx
│   └── main.tsx
├── .env.example          # modelo das variáveis de ambiente
├── index.html
├── package.json
├── postcss.config.cjs
├── tsconfig.json
├── vite.config.ts
└── README.md
```

---

## 🔑 Variáveis de ambiente

Crie um arquivo **.env** na raiz do projeto com base no arquivo `.env.example`:

```
VITE_API_URL=https://suaapi.com
VITE_API_KEY=sua_chave_aqui
```

---

## 🚀 Instalação e execução local

1. **Clone o repositório**
```bash
git clone https://github.com/seuusuario/seu-repositorio.git
```

2. **Acesse a pasta do projeto**
```bash
cd seu-repositorio
```

3. **Instale as dependências**
```bash
npm install
```

4. **Configure as variáveis de ambiente**
```bash
cp .env.example .env
```

5. **Execute o projeto**
```bash
npm run dev
```

6. **Build para produção**
```bash
npm run build
```
