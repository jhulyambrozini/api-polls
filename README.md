# API POLLS
Este projeto foi feito durante a NLW Expert da Rocketseat na trilha com foco em back end com Node.js

Ele consiste em uma API para equetes, que possui as rotas HTTP de:
- Criar uma enquete (POST: /polls)
- Buscar por uma enquete específica (GET: polls/:pollId)
- Votar em uma enquete (POST: polls/:pollId/votes)

E a rota WebSocket de:
- Buscar pela quantidade de votos nas opções de uma enquete (WS: /polls/:pollId/results)

## Tecnologias usadas
- **Node.js**:
Um ambiente de tempo de execução JavaScript que permite aos desenvolvedores executar código JavaScript no lado do servidor. Node.js é conhecido por sua escalabilidade e eficiência, sendo amplamente utilizado para construir aplicativos da web e APIs.

- **Fastify**:
Um framework web leve e eficiente para Node.js, projetado para lidar com uma grande carga de solicitações de forma rápida e eficiente. Fastify é conhecido por sua velocidade de execução e baixa sobrecarga, tornando-o uma escolha popular para a construção de APIs de alto desempenho.

- **TypeScript**:
Uma linguagem de programação de código aberto que é uma superset da linguagem JavaScript. TypeScript adiciona tipagem estática opcional e outros recursos avançados para ajudar os desenvolvedores a escreverem código mais seguro e escalável.

- **Prisma**:
Uma ferramenta de ORM (Object-Relational Mapping) para Node.js e TypeScript, que simplifica a interação com bancos de dados relacionais. Prisma oferece uma API de consulta tipo-safe e gera código automaticamente com base no modelo de dados definido pelo desenvolvedor.

- **Redis**:
Um banco de dados de estrutura de dados em memória que é conhecido por sua velocidade e capacidade de armazenamento de dados chave-valor. Redis é comumente utilizado para caching, gerenciamento de sessão, filas de mensagens e outras aplicações onde o acesso rápido aos dados é crucial.

- **PostgreSQL**:
Um sistema de gerenciamento de banco de dados relacional de código aberto conhecido por sua confiabilidade, robustez e suporte para recursos avançados. PostgreSQL é amplamente utilizado em aplicações web e oferece suporte para transações ACID, integridade referencial e consultas complexas.

- **Zod**:
Uma biblioteca de validação de esquema TypeScript que permite aos desenvolvedores definir e validar esquemas de dados de forma segura e eficiente. Zod utiliza o sistema de tipos do TypeScript para garantir a integridade dos dados em tempo de compilação.

- **Websocket**:
Um protocolo de comunicação bidirecional que permite a comunicação em tempo real entre clientes e servidores web. Websockets permitem a criação de aplicativos da web interativos e em tempo real.

- **HTTP (Hypertext Transfer Protocol)**:
Um protocolo de comunicação utilizado para transferir dados pela World Wide Web. HTTP define os métodos de requisição e resposta entre clientes e servidores web, permitindo a transferência de recursos da web.

- **Docker**:
Uma plataforma de software que simplifica o processo de criação, implantação e execução de aplicativos em contêineres. Docker permite que os desenvolvedores empacotem suas aplicações junto com suas dependências em contêineres, garantindo que elas funcionem de maneira consistente em qualquer ambiente.

## Execução
- 1 Dá um fork neste repositório
- 2 Clone ou baixe o seu repositório fork
- 3 Abra seu terminal e navegue até a pasta do projeto
- 4 Rode o commando `npm i` ou `npm install` para baixar as dependências
- 5 Abra seu Docker Desktop
- 6 Rode o comando `docker compose up -d` para iniciar os bancos de dados no docker
- 7 Rode o commando `npm run dev` para iniciar a API em modo de desenvolvimmento
