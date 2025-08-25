# 🎬 MovieFinder
Projeto Web: Um aplicativo web para buscar, favoritar e descobrir filmes.

OBS: Este é um projeto fictício, para fins de estudo.

<br/>

---

<br/>

## 📌 Funcionalidades
- 🔍 Buscar filmes por título
- 🎭 Filtrar por gênero e ano
- ⭐ Ver detalhes (sinopse, elenco, nota, pôster)
- ❤️ Favoritar filmes e salvar no navegador
- 🎥 Recomendações baseadas em um filme escolhido

  <br/>

## 🧠 Tecnologias utilizadas
- ⚛️ React + Vite (TypeScript)
- 🎨 Tailwind CSS
- 📦 Zustand para estado
- 🌐 API TMDb / OMDb
- 🧹 ESLint + Prettier

<br/>

## ▶️ Como rodar o projeto

1. Clone este repositório

- git clone https://github.com/seu-usuario/moviefinder.git
cd moviefinder

2. Instale as dependências

- npm install

3. Configure o arquivo .env

- VITE_MOVIE_API_KEY=SUA_CHAVE_API
- VITE_MOVIE_API_BASE=https://api.themoviedb.org/3

4. Execute em modo desenvolvimento

- npm run dev

<br/>

## 📂 Estrutura de pastas

moviefinder/

├─ src/

│  ├─ api/         → Funções de requisição à API

│  ├─ components/  → Componentes reutilizáveis

│  ├─ pages/       → Páginas principais (Home, Detalhes, Favoritos)

│  ├─ store/       → Gerenciamento de favoritos com Zustand

│  ├─ types/       → Tipagens TypeScript

│  └─ App.tsx      → Roteamento simples

├─ public/         → Imagens e favicon

├─ .env.example    → Exemplo de variáveis de ambiente

├─ package.json

└─ README.md

<br/>

## 📜 Licença

Este projeto está sob a Licença MIT.
Sinta-se livre para usar e modificar como quiser.

<br/>

O app consome uma API pública de filmes (ex.: TMDb ou OMDb) e foi pensado para ser simples de configurar e rodar.
