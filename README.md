# 🛍️ E-Sale

## 📌 Sobre o projeto

Projeto criado com o intúito de aprofundar meus conhecimentos em arquitetura de 𝗺𝗶𝗰𝗿𝗼𝘀𝘀𝗲𝗿𝘃𝗶ç𝗼𝘀 utilizando o ecossistema
𝗝𝗮𝘃𝗮 com Spring Boot. A proposta foi desenvolver um sistema de e-commerce dividido em múltiplos serviços independentes,
permitindo explorar na prática conceitos importantes de arquitetura distribuída.

O sistema foi estruturado em diferentes microsserviços responsáveis por domínios específicos da aplicação, como
clientes, produtos, vendas e pagamentos. Cada serviço possui sua própria responsabilidade e lógica de negócio, seguindo
o princípio de separação de responsabilidades, comum em arquiteturas de microsserviços. Esse modelo permite que cada
serviço seja desenvolvido, mantido e escalado de forma independente.

Durante o desenvolvimento do projeto, foram exploradas diversas tecnologias e práticas utilizadas em aplicações
modernas, como o 𝗠𝗶𝗿𝗼 para idealização e representação visual do fluxo e dos processos da aplicação, o 𝗚𝗶𝘁𝗛𝘂𝗯
𝗣𝗿𝗼𝗷𝗲𝗰𝘁𝘀 para gerenciamento do projeto, 𝗦𝗽𝗿𝗶𝗻𝗴 𝗕𝗼𝗼𝘁 e 𝗦𝘄𝗮𝗴𝗴𝗲𝗿 para criação e documentação das 𝗔𝗣𝗜𝘀, 𝗢𝗽𝗲𝗻𝗙𝗲𝗶𝗴𝗻 e
𝗔𝗽𝗮𝗰𝗵𝗲 𝗞𝗮𝗳𝗸𝗮 para comunicação entre os microserviços, 𝗗𝗼𝗰𝗸𝗲𝗿 para conteinerização das aplicações, Mercado Pago para
criação de links de pagamento e o 𝗠𝗼𝗻𝗴𝗼𝗗𝗕 para armazenamento dos dados dos microserviços.
Esse processo permitiu compreender melhor os desafios envolvidos em sistemas distribuídos, como comunicação entre
serviços,
tratamento de falhas e organização da lógica de negócio.

Além disso, o projeto foi pensado como um ambiente de aprendizado e experimentação, permitindo aplicar na prática
conceitos estudados sobre microsserviços, 𝗺𝗲𝗻𝘀𝗮𝗴𝗲𝗿𝗶𝗮, 𝗮𝗿𝗾𝘂𝗶𝘁𝗲𝘁𝘂𝗿𝗮 𝗱𝗲 𝘀𝗼𝗳𝘁𝘄𝗮𝗿𝗲 e boas práticas de
𝗱𝗲𝘀𝗲𝗻𝘃𝗼𝗹𝘃𝗶𝗺𝗲𝗻𝘁𝗼 𝗯𝗮𝗰𝗸𝗲𝗻𝗱. A construção desse sistema também contribui para consolidar conhecimentos em modelagem de
serviços, documentação de APIs e organização de projetos em larga escala.

#### O projeto também está postado no [LinkedIn](www.linkedin.com/in/jobson-de-oliveira).

## Ferramentas Utilizadas

- Java 17
- Spring Boot
- Maven
- OpenFeign
- MongoDB
- Apache Kafka
- Swagger
- Docker
- Git
- GitHub
- GitHub Projects
- Miro
- Postman
- Mercado Pago (API)
- IntelliJ IDEA

## Microserviços

- [Client](https://github.com/JobsonDeveloper/Client-Microservice)
- [Product](https://github.com/JobsonDeveloper/Product-Microservice)
- [Sale](https://github.com/JobsonDeveloper/Sale-Microservice)
- [Payment](https://github.com/JobsonDeveloper/Payment-Microservice)

## Mapeamento do sistema no Miro 

[Visualizar](https://miro.com/welcomeonboard/WDd5bTU0KzA5eGNUY0dpMlRncU05V0pDendOQzlHUXVJZ2k4aUtWT2JyRm1tTVU2Q1F1VUNpNkJPRFlUYWVLZldTK1BXQnNId2N2NXZWeDVJc2hxR0pNM0VWNjh4QnovbGlSSGphRTJsdUt3QWVUSExjdkVGSnJmSWtOV0ZKczhzVXVvMm53MW9OWFg5bkJoVXZxdFhRPT0hdjE=?share_link_id=666215258423)


## Gerenciamento do projeto (Kanban)



## Como testar

1. Faça um fork dos microserviços.
2. Use o comando abaixo para subir as imagens no Docker:

```
docker compose up --build
```
3. Faça um fork deste projeto e suba o Apache Kafka e o MongoDB no Docker com o comando abaixo:

```
docker compose up --d
```

4. Após iniciar todo, você poderá visualizar as documentações através da rota:

```
http://localhost:(8082,8083,8084 ou 8085)/swagger-ui/index.html
```