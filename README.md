<h1 align="center">Desafio - TDD Event-City</h1>

<p align='center'> 
    <img src="https://img.shields.io/badge/Spring_Boot-F2F4F9?style=for-the-badge&logo=spring-boot"/>
    <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white"/>  
</p>    
O Desafio proposto pela DevSuperior teve como objetivo implementar as funcionalidades necessárias para que os testes de integridade web do projeto já especificados passem, usando o princípio do TDD(Test Driven Development).

<h2>Veja o projeto</h2>

Experimente live demo [aqui](https://i.imgur.com/DfLfi42.gif).

![](http://imageshack.com/a/img924/1599/97tibd.gif)

<img src="https://i.imgur.com/DfLfi42.gif"/> 

<h2>Como criar e executar o Event-City localmente</h2>

Criar e executar o projeto em seu ambiente de desenvolvimento local é muito fácil. Certifique-se de ter o Git, JDK17 instalados e siga as instruções abaixo. Precisa de informações adicionais? entre em contato no e-mail josecarloscjj@gmail.com 
(Estas instruções pressupõem que você esteja instalando como um usuário root.)

1. Clone o código fonte

   ```bash
   git@github.com:joosecj/EventCityTDD.git
   ```

2. Em sua IDE de preferência(utilizei Intellij), importe a pasta **backend** e faça o update das dependências do **maven**.

3. Ao executar o projeto, pode ser acessado um navegador da Web em http://localhost:8080/

4. Abaixo, encontra-se as requisições GET/PUT/DELETE E UPDATE.

## Requisições (Endpoints)

#### Obs: Para testar as requisições, poderá usar o URL na nuvem ou local que e http://localhost:8080.

- *All City Sorted By Name* - **GET**

   ```bash
   http://localhost:8080/cities
   ```
   ##

- *Nova City -* **POST**

   ```bash
   http://localhost:8080/cities
   ```

   ##

- *Pessoa -* **DELETE**

   ```bash
   http://localhost:8080/cities/2
   ```

   ##

- *Corpo da Requisição(Body) - City -* **JSON** - **POST**

   ```bash
  {
    "name": "Recife"
  }
   ```
   ##

   - *Pessoa -* **PUT**

   ```bash
   http://localhost:8080/events/1
   ```

   ##

   - *Corpo da Requisição(Body) - Event -* **JSON** - **PUT**

   ```bash
  {
    "name": "Expo XP",
    "date": "2021-05-18",
    "url": "https://expoxp.com.br",
    "cityId": 7
  }
   ```
   ##

   <h2>Tecnologias utlizadas</h2>

   - [Java](https://docs.oracle.com/en/java/javase/17/)
   - [Spring Boot](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/)
   - [JPA](https://docs.spring.io/spring-data/jpa/docs/current/reference/html/)
   - [Maven](https://maven.apache.org/guides/)
   - [H2 Database](https://www.h2database.com/html/main.html)
   - Teste Automatizados com [JUnit](https://junit.org/junit5/docs/current/api/)
   - [Postman](https://www.postman.com/api-documentation-tool/)

   ##

   <div align="center">
   <h2>Autor: José Carlos</h2>
      <img align="center" alt="Jose-Js" height="190" width="190" src="https://avatars.githubusercontent.com/u/100246121?s=400&u=b15a545fb2c49f97f84e25aa0520b8b525631384&v=4"
   </div>
   </br> 
   </br>
   <div align="center">
      <a href="https://instagram.com/joosecj" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
      <a href = "mailto:josecarloscjj@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
      <a href="https://www.linkedin.com/in/jos%C3%A9-carlos-a79736a0/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
   </div>