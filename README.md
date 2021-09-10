## (Bootcamp Dio) Criando uma Solução de E-Commerce com Microsserviços em Java

Desenvolvimento de uma solução de e-commerce com arquitetura de microsserviços
e aplicação da integração entre eles orientada a eventos com Apache Kafka e garantir a compatibilidade da comunicação dos microsserviços com Schema Registry. Linguagem utilizada é o Java em combinação com a stack do Spring Spring Boot, Spring Cloud Streams).

**DEFINIÇÕES DO PROJETO:**

- **Domínios**
  - E-Commerce -> Checkout
  
  - E-Commerce -> Payment 
- **Arquitetura** (Orientada a Eventos)
  
  - Checkout Front
  - Checkout API
  - Payment API
- **Apache Kafka**
  - Apache Kafka é uma plataforma open-source de processamento de streams e tem como objetivo fornecer uma plataforma unificada, de alta capacidade e baixa latência para tratamento de dados em tempo real.

- **Apache Zookeeper**
  - Apache ZooKeeper é um servidor de código aberto para coordenação distribuída altamente confiável de aplicativos em nuvem.
- **Schema Registry**
  - Schema Registry fornece uma camada de serviço para os metadados das mensagens. Ele provê uma interface RESTful para armazenar e recuperar schemas Avro, JSON Schema e Protobuf, e ele utiliza o próprio Apache Kafka como camada de armazenamento..
- **Apache Avro**
  - Apache Avro é uma estrutura de serialização de chamada e procedimento remoto orientada a linhas, desenvolvida no projeto Hadoop do Apache. Ele usa JSON para definir tipos e protocolos de dados e serializa dados em um formato binário compacto.

- **Serviços de Stream**
  - Streaming Data é um fluxo continuo de dados oriundo de diversas fontes. Coleta, processa e armazena um grande volume de dados em tempo real; alta disponibilidade de dados e confiabilidade.
  
  - Ex.: Microsoft Event Hub, Amazon Kinesis e Google Pub/Sub.
  
    
  
- **SOLID - 5 Princípios da POO**

1. **S — Single Responsiblity Principle** (Princípio da responsabilidade única)
2. **O — Open-Closed Principle** (Princípio Aberto-Fechado)
3. **L — Liskov Substitution Principle** (Princípio da substituição de Liskov)
4. **I — Interface Segregation Principle** (Princípio da Segregação da Interface)
5. **D — Dependency Inversion Principle** (Princípio da inversão da dependência)

Esses princípios ajudam o programador a escrever [códigos mais limpos](https://medium.com/joaorobertopb/1-clean-code-o-que-é-porque-usar-1e4f9f4454c6), separando responsabilidades, diminuindo acoplamentos, facilitando na refatoração e estimulando o reaproveitamento do código.





