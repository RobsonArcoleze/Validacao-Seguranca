# Validacao / Seguranca 
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/devsuperior/sds1-wmazoni/blob/master/LICENSE) 

# Sobre o projeto

Projeto desenvolvido para aprovação no módulo de Validação e Segurança do BootCamp Spring / React  da DevSuperior.

Projeto criado com a metodologia TDD, desenvolvido o projeto conforme os testes de integração criados!

![Testes](https://github.com/RobsonArcoleze/Validacao-Seguranca/blob/main/img/testes.png)

**Enunciado:**

Neste sistema, somente as rotas de leitura (GET) de eventos e cidades são públicas (não precisa de login). 
Usuários CLIENT podem também inserir (POST) novos eventos. Os demais acessos são permitidos apenas a usuários ADMIN.


**VALIDAÇÕES DE CITY**

- Nome não pode ser vazio


**VALIDAÇÕES DE EVENT**

- Nome não pode ser vazio
- Data não pode ser passada
- Cidade não pode ser nula

## Modelo conceitual
![Modelo Conceitual](https://github.com/RobsonArcoleze/Validacao-Seguranca/blob/main/img/modeloConceitual.png)


# Tecnologias utilizadas


- Java
- Spring Boot
- Spring Data
- JPA / Hibernate
- Maven
- DB h2
- Junit
- Mockito
- Spring Security
- OAuth2
- Bean Validation

# Como executar o projeto

## Back end
Pré-requisitos: Java 11+

```bash
# clonar repositório
git@github.com:RobsonArcoleze/Validacao-Seguranca.git

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

# Testando o projeto

**Collection do Postman:**


https://www.getpostman.com/collections/e1f59c905aeca84c1ebc


**NECESSÁRIO CONFIGURAR VARIÁVEIS DE AMBIENTE**

**Clicar em NEW!**


![new](https://github.com/RobsonArcoleze/Validacao-Seguranca/blob/main/img/new.png)


**Enviroment**


![Enviroment](https://github.com/RobsonArcoleze/Validacao-Seguranca/blob/main/img/enviromente.png)


**ADD Variavel**

![variavel](https://github.com/RobsonArcoleze/Validacao-Seguranca/blob/main/img/addVariable.png)


**Escolha ela na seta para baixo, e depois confira com o olhinho**

![Visualization](https://github.com/RobsonArcoleze/Validacao-Seguranca/blob/main/img/visualization.png)

# Autor

Robson de Oliveira Arcoleze

https://www.linkedin.com/in/robsonarcoleze/
