# Caderno Temático: Arquitetura Orientada a Eventos (EDA)

##  Sobre o Projeto

Este projeto foi desenvolvido como parte do desafio da DIO com o objetivo de estudar e documentar conceitos sobre **Arquitetura Orientada a Eventos (Event-Driven Architecture - EDA)** utilizando o **NotebookLM** como ferramenta de aprendizado apoiada por Inteligência Artificial.

A arquitetura orientada a eventos é amplamente utilizada em sistemas modernos, microsserviços, aplicações escaláveis e ambientes cloud.

---

#  Objetivos de Estudo

- Entender o conceito de Event-Driven Architecture
- Conhecer produtores, consumidores e brokers
- Estudar ferramentas como Kafka e RabbitMQ
- Identificar vantagens e desafios
- Aplicar EDA em projetos reais com Java + Spring Boot

---

#  Fontes Utilizadas no NotebookLM

##  Documentações e Materiais

1. Microsoft Learn  
https://learn.microsoft.com/en-us/azure/architecture/guide/architecture-styles/event-driven

2. AWS  
https://aws.amazon.com/event-driven-architecture/

3. RabbitMQ Docs  
https://www.rabbitmq.com/tutorials.html

4. Confluent Kafka  
https://developer.confluent.io/

5. Red Hat  
https://www.redhat.com/en/topics/integration/what-is-event-driven-architecture

---

#  Prompts Utilizados no NotebookLM

## Prompt 1:
Explique arquitetura orientada a eventos de forma simples.

## Prompt 2:
Qual diferença entre arquitetura monolítica e orientada a eventos?

## Prompt 3:
Explique Kafka vs RabbitMQ com exemplos reais.

## Prompt 4:
Crie um fluxo de pedido usando Java Spring Boot e eventos.

## Prompt 5:
Quais desafios existem em sistemas orientados a eventos?

---

#  Miniguia Final de Estudos

# O que é EDA?

É um modelo onde sistemas se comunicam através de eventos.

Exemplo:

- Pedido criado
- Pagamento aprovado
- Usuário cadastrado

Cada evento dispara ações em outros sistemas.

---

#  Componentes

## Producer
Quem gera o evento.

## Consumer
Quem consome o evento.

## Broker
Intermediador que distribui mensagens.

Exemplos:

- Kafka
- RabbitMQ
- AWS SNS/SQS

---

# Vantagens

- Escalabilidade
- Baixo acoplamento
- Processamento assíncrono
- Alta performance
- Fácil integração

---

#  Desafios

- Rastreamento distribuído
- Retries
- Ordem de mensagens
- Duplicidade
- Monitoramento

---

# Glossário

| Termo | Significado |
|------|------------|
| Event | Algo aconteceu |
| Producer | Produz evento |
| Consumer | Consome evento |
| Queue | Fila |
| Topic | Canal |
| Broker | Distribuidor |

---

# Onde é Usado?

- Bancos
- E-commerce
- Uber
- Netflix
- IoT
- Microsserviços

---

#  Conclusão

EDA é uma das arquiteturas mais importantes do mercado atual e fundamental para quem deseja atuar com backend, cloud e sistemas escaláveis.

---

# 👩‍💻 Autora

Marcelle Santos
