# Desenvolvimento de testes unitários para validar uma API REST de gerenciamento estoques de cerveja

### Objetivo: Projeto desenvolvido para aplicação de conhecimentos no Bootcamp Banco Inter da Digital Innovation One - para implementar testes, unitariamente, em uma API REST para o gerenciamento de estoques de cerveja. Foi desenvolvido testes unitários para validar o sistema de gerenciamento de estoques de cerveja, e também apresentar os principais conceitos e vantagens de criar testes unitários com JUnit e Mockito.

### Durante o bootcamp, foram abordados os seguintes tópicos:

* Baixar um projeto através do Git para desenolver nossos testes unitários. 
* Apresentação conceitual sobre testes: a pirâmide dos tipos de testes, e também a importância de cada tipo de teste durante o ciclo de desenvolvimento.
* Foco nos testes unitários: mostrar o porque é importante o desenvolvimento destes tipos de testes como parte do ciclo de desenvolvimento de software.
* Principais frameworks para testes unitários em Java: JUnit, Mockito e Hamcrest. 
* Desenvolvimento de testes unitários para validação de funcionalides básicas: criação, listagem, consulta por nome e exclusão de cervejas.
* TDD: apresentação e exemplo prático em 2 funcionaliades importantes: incremento e decremento do número de cervejas no estoque.

### [Neste link](https://drive.google.com/file/d/1KPh19mvyKirorOI-UsEYHKkmZpet3Ks6/view?usp=sharing), os slides apresentados como o roteiro utilizado para o desenvolvimento do projeto foi disponibilizado.


### Para executar o projeto no terminal, digite o seguinte comando:

```shell script
mvn spring-boot:run 
```

### Para executar a suíte de testes desenvolvida durante a live coding, basta executar o seguinte comando:

```shell script
mvn clean test
```

### Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/api/v1/beers
```

## Stack utilizada
* Java 14
* Maven
* Spring Boot
* Frameworks JUnit, Mockito e Hamcrest
* Intellj IDEA Community Edition
* GIT.

### Abaixo, alguns links para desenvolver conhecimento sobre tópicos mencionados durante o bootcamp:

* [SDKMan! para gerenciamento e instalação do Java e Maven](https://sdkman.io/)
* [Referência do Intellij IDEA Community, para download](https://www.jetbrains.com/idea/download)
* [Palheta de atalhos de comandos do Intellij](https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf)
* [Site oficial do Spring](https://spring.io/)
* [Site oficial JUnit 5](https://junit.org/junit5/docs/current/user-guide/)
* [Site oficial Mockito](https://site.mockito.org/)
* [Site oficial Hamcrest](http://hamcrest.org/JavaHamcrest/)
* [Referências - testes em geral com o Spring Boot](https://www.baeldung.com/spring-boot-testing)
* [Referência para o padrão arquitetural REST](https://restfulapi.net/)
* [Referência pirâmide de testes - Martin Fowler](https://martinfowler.com/articles/practical-test-pyramid.html#TheImportanceOftestAutomation)


