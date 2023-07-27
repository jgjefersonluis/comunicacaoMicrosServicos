<h1>Comunicação entre microsserviços</h1>

<p> Como aplicá-las? </p>
<p>
Criar 3 APIs, duas delas com Node.js, MongoDB, Mongoose, Sequelize, PostgreSQL e JWT para autenticação.
Será craida uma API com Java 11 utilizando Spring Boot, PostgreSQL, Spring Data JPA, Spring Cloud OpenFeign e JWT, 
realizando a comunicação e integração entre essas duas tecnologias.</p>

<p>
O RabbitMQ para a comunicação via filas de mensagens utilizando o protocolo AMQP com o objetivo
de criar uma comunicação assíncrona entre os serviços.
Também utilizaremos comunicação síncrona entre aplicações, chamadas a clients HTTP entre as APIs, 
integrando-as com as tecnologias FeignClient (Spring Boot) e Axios (Node.js).
</p>
<p>
Todas as nossas aplicações em containers Docker utilizando o Docker-compose.
O deploy de toda a arquitetura na AWS utilizando os serviços AWS Elastic Beanstalk, Amazon RDS e Amazon CloudWatch!
Implementar um básico de rastreabilidade de requisições entre microsserviços com logs nas APIs, IDs de requisições
e iremos visualizar nossa rastreabilidade através dos logs da aplicação.
</p>