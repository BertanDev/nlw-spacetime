# 🌌 Nlw Spacetime 🌌

Aplicação criada durante o evento Nlw da @Rocketseat, onde utilizamos a nova versão do Next 13, junto com outras diversas tecnologias do ecossistema JavaScript

## ▶️ Testando aplicação

Com a aplicação em sua máquina, rode na raiz da pasta server e da pasta web:
```
npm install
```

em seguida:
```
npm run dev
```

> **Note**        
> A api irá rodar na porta ```3333```, e a aplicação web na porta ```3000```

## 💠 Funcionalidades da aplicação

- Realizar Login utilizando o GitHub
- Fazer Logout
- Cadastrar uma lembrança
- Fazer upload de um arquivo de imagem ou vídeo junto da lembrança
- Listar todas as suas lembranças

## 🧪 Rotas da Api

- GET ```/memories``` Rota para listagem das lembranças de um usuário
- GET ```/memories/:id``` Rota que retorna dados de uma lembrança
- POST ```/register``` Rota para login/cadastro
- POST ```/upload``` Rota para fazer upload de imagens e vídeos
- POST ```/memories``` Rota para criação de uma memória
- PUT ```/memories/:id``` Rota para atualização de uma memória
- DELETE ```/memories/:id``` Rota para deletar uma memória

## 🔱 Ferramentas utilizadas  

- React com Next 13 
- TypeScript
- Node.js
- Fastify
- Prisma
- Axios
- Zod
- Tailwind
- Eslint
- Dayjs
- @fastify/jwt e jwt-decode
- Js-cookie
- Lucide-react
- @fastify/cors /static /multipart

## Imagens da aplicação Web
![No memories](https://github.com/BertanDev/nlw-spacetime/assets/72395637/89517db8-fc9c-4bbc-9bf1-acaef7593e52)
![Group 48095558](https://github.com/BertanDev/nlw-spacetime/assets/72395637/bd515aee-0626-4e3b-8496-dddbacd6fe5c)
![Group 48095559](https://github.com/BertanDev/nlw-spacetime/assets/72395637/0588a29d-e555-434b-9399-ced77f81509d)

