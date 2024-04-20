## 💻 ApiSolid

Projeto backend em NodeJS, desenvolvido para solucionar o desafio de Solid da Rocketseat. Trata de um projeto para organizações que cuidam de adoção de pets afim de arrumar um lar para os mesmos.

## 🚀 Começando

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.

Veja **[clone](https://github.com/EngJao89/pizzashop-reactjs.git)** para saber como clonar o repositório para sua máquina.

### 🔧 Instalação

Para rodar o projeto após clonar na sua máquina. Será necessário seguir as etapas a seguir.

Comece com seu empacotador padrão:

```
npm install
```

Ou utilize:

```
yarn install
```

Após instalar as dependencias suba o container do docker com PostgreSQL rode:

```
docker compose up
```

Após subir o container do docker, faça as migrações do banco rode:

```
npx prisma migrate dev
```

Ao terminar siga a proxima etapa para rodar o projeto:

Para rodar o projeto:

```
npm run dev
```

Ou utilize:

```
yarn dev
```
