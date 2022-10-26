# roteiro-01-DAC

Atividade de Desenvolvimento de Aplicações Corporativas

## Pré-requisitos

:warning: [Docker](https://www.docker.com/)
:warning: [MongoDB Atlas](https://www.mongodb.com/atlas)

Configurando:

- Instale o Docker na sua maquina

- clone este repositorio [git clone https://github.com/Rebehk/roteiro-01-DAC.git]

  $ docker build -t app .

  $ docker run -d -p 3000:3000 app

- Crie um arquivo .env com a varivel MONGO_URL com a string de conexão do MongoDB Atlas

### respostas da atividade

- Principais vantagens do uso de containers são a portabilidade, agilidade, escalabilidade, controle e isolamento em todo o fluxo entre o Desenvolvimento e Operações.
- Particularmente tive varios problemas ao usar o docker desktop no windows, efoi um pouco complexo entender como usar.
