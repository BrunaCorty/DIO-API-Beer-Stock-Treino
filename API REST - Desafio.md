### <u>API REST - Desafio de gerenciamento de estoques de cerveja</u>



## Live coding, onde aprendemos, unitariamente, uma API REST para o gerenciamento de estoques de cerveja. Desenvolvimento de testes unitários para validar o nosso sistema de gerenciamento de estoques de cerveja, e também apresentar os principais conceitos e vantagens de criar testes unitários com JUnit e Mockito.

Meu primeiro passo foi criar uma Pasta no meu Desktop e nela armazenar os arquivos.
O Typora (extenção .md) foi o programa escolhido por mim para escrever as anotações de projeto.
Em seguida fui no site do Spring Boot (https://start.spring.io/) para escolher as dependências do meu projeto Maven na linguagem Java 17.

As dependências escolhidas foram:
- Spring Boot Dev Tools
- Lombok (Biblioteca Java)
- H2 Database (Banco de Dados)
- Spring Web
- Rest Repository
- Spring Data JPA

O link de compartilhamento da Configuração acima é: https://start.spring.io/#!type=maven-project&language=java&platformVersion=2.5.5&packaging=jar&jvmVersion=17&groupId=com.digitalinnovation&artifactId=Stock&name=Stock&description=Beer%20stock%20project%20for%20Spring%20Boot&packageName=com.digitalinnovation.Stock&dependencies=devtools,lombok,web,data-rest,h2,data-jpa

O Spring Boot gerou um arquivo do tipo Zip que abri no programa IntelliJ, na versão IDEA Community Edition 2021.2 e os plugins JUnit 5 Mockito, JUnit Generator V2.0 e Swagger 2 ativados, objetivam escrever testes repetíveis simples e automatizados.

Em paralelo,com o GitHub aberto, criei um novo Repositório para abrigar as tarefas acima mencionadas.

Durante a aula foram abordados os seguintes tópicos:

- Baixar um projeto através do Git para desenolver nossos testes unitários.
- Apresentação conceitual sobre testes: a pirâmide dos tipos de testes, e também a importância de cada tipo de teste durante o ciclo de desenvolvimento.
- Foco nos testes unitários: mostrar o porque é importante o desenvolvimento destes tipos de testes como parte do ciclo de desenvolvimento de software.
- Principais frameworks para testes unitários em Java: JUnit, Mockito e Hamcrest.
- Desenvolvimento de testes unitários para validação de funcionalides básicas: criação, listagem, consulta por nome e exclusão de cervejas.
- TDD: apresentação e exemplo prático em 2 funcionaliades importantes: incremento e decremento do número de cervejas no estoque.

Para executar o projeto no terminal, executou-se o comando:

```
mvn spring-boot:run 
```

Para executar a suíte de testes desenvolvida durante a live coding, executamos o seguinte comando:

```
mvn clean test
```

Foram necessários os seguintes pré-requisitos para a execução do projeto desenvolvido durante a aula:

- Java 14 ou versões superiores.
- Maven 3.6.3 ou versões superiores.
- Intellj IDEA Community Edition ou sua IDE favorita.
- Controle de versão GIT instalado na sua máquina.
