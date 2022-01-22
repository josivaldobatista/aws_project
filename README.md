# Projeto de estudo para AWS curso da Udemy Criando microsserviços em Java com AWS ECS e Fargate

## Infraestrutura de microsserviços em cluster com AWS CDK e serviços da AWS como ECS, SNS, SQS, RDS, DynamoDB e S3.

### Descrição

Nesse curso você irá criar dois microservices utilizando Spring Boot em containers Docker, para interagir com serviços da AWS como:
* ECS: o Elastic Container Service é o serviço de orquestração de containers da AWS. Com ele é possível gerenciar a execução de microsserviços baseados em containers Docker de forma robusta e escalável. E com o AWS Fargate, o Serverless compute for containers da AWS, não é necessário criar instâncias de máquinas EC2, reduzindo o custo de operação de aplicações baseadas em containers;

* RDS: o Relational Database Service é um recurso que permite a criação de instâncias de banco de dados, com serviços como backups automáticos e diretrizes de segurança de acesso;

* SNS: o Simple Notification Service é um recurso muito utilizado para criação de mecanismos de notificações para diversas aplicações ou outros serviços;

* SQS: o Simple Queue Service é um recurso que permite a criação de filas para entrega de mensagens de forma rápida e confiável, possibilitando a criação de um mecanismo assíncrono de comunicação entre aplicações;

* DynamoDB: esse é um poderoso serviço de banco de dados NoSQL, que permite a criação de tabelas, sem a necessidade de se criar um servidor, com características exclusão automática de dados, escalabilidade e muito mais;

* S3: o Simple Storage Service permite a criação de buckets para armazenamento seguro de arquivos. Além disso é possível configurar eventos a serem gerados quando esses arquivos são colocados nesses buckets, fazendo com outras aplicações sejam avisadas desses eventos.

Com isso você aprenderá também a utilizar o AWS SDK, que é um conjunto de bibliotecas desenvolvido pela própria AWS para utilizar seus serviços. Esses recursos serão criados na AWS utilizando o AWS Cloud Development Kit - CDK, uma forma moderna de modelamento e provisionamento de infrastrutura na AWS. Você também aprenderá como monitorar os serviços através de gráficos e métricas, além de utilizar o CloudWatch Insights, para visualização e pesquisa de logs das aplicações. Aprenda tudo isso com explicações detalhadas e exercícios práticos, onde você poderá testar suas habilidades e aplicar os conceitos aprendidos. Ao final desse curso, você estará confiante para arquitetar e desenvolver serviços na AWS de forma escalável e robusta.