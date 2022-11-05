<p align="center">
  <img src="./assets/logo.svg" />
  <hr />
</p>
<p align="center">
  Projeto desenvolvido durante a NLW (Next Level Week) da Rocketseat
</p>
<br>

# Sobre o projeto
Uma plataforma que permite que usuários criem e participem de bolões. A aplicação web tem o objetivo de apenas criar bolões, enquanto o app mobile 
possui todas as outras funcionalidades do sistema

<img src="./assets/Web.png" alt="drawing" width="800"/>

# Tecnologias utilizadas
- React
- React Native
- Native Base
- NextJs
- Tailwind CSS
- Expo
- Node.js
- Prisma
- SQLite

# Inicialização
## Server
entre na pasta `server` presente no diretório raiz, e rode o comando para instalar as dependências:
```bash
npm i
```
Agora para criar o banco de dados, rode o comando:
```bash 
npx prisma migrate dev
```
Por fim para iniciar o servidor, rode o comando:
```bash
npm run dev
```

## Web
Para rodar o projeto web, entre na pasta `web` presente no diretório raiz, e rode o comando para instalar as dependências:
```bash
npm i
```
Agora para iniciar o projeto, rode o comando:
```bash
npm run dev
```
> Atenção: não esqueça de iniciar o servidor antes de iniciar o projeto web
