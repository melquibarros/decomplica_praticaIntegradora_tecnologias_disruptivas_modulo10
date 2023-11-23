# Aplicação React de Gerenciamento de Projetos e Tarefas

Projeto criado com as bibliotecas React JS e Material UI.

## Passo-a-passo para execução em browser local

1. Clonar o repositório
2. Localmente, entrar na pasta do projeto e instalar as dependências:
   `
   npm install
   `
3. Executar a aplicação:
   `
   npm start
   `
## Passo-a-passo para execução docker

1. Clonar o repositório
2. Localmente, entrar na pasta do projeto e buildar imagem docker
   `
   docker build -t image-tag ./
   `
3. Execute o container 
   `
   docker run -p 127.0.0.1:8080:3000 image-tag
   `
3. acesse o container pelo browser
   `
   http://127.0.0.1:8080/
   `