[Voltar](intro.md)

# Apache Maven

## O que é o Maven

O nome Maven vem de uma língua germânica e significa acumulador de conhecimento. Trata-se de uma ferramenta para gerenciar e construir projetos baseados em Java.[^1]

## Origem

O Maven surgiu como uma tentativa de facilitar o processo de construção do [Turbine](https://turbine.apache.org/), um framework de desenvolvimento web rápido, dentro do projeto Jakarta.[^1]

O projeto Jakarta foi um guarda-chuva de vários projetos, sendo alguns dos mais famosos o próprio Maven, Tomcat e Ant.[^1]

O Maven surgiu devido à dificuldade em gerenciar e construir os projetos usando Ant, uma vez que cada processo tinha seus arquivos JAR de uma maneira diferente, tornando difícil o compartilhamento entre projetos e a possibilidade de reuso. O Maven surgiu com o objetivo de permitir um gerenciamento, compartilhamento e publicação fáceis de projetos Java.[^1]

## Objetivos

### Facilitar o processo de construção

O Maven permite que o desenvolvedor não precise entender profundamente o processo de construção de um projeto, porém não elimina a necessidade de saber como funciona.[^1]

### Criar um sistema de construção padronizado

O Maven utiliza seu modelo de objeto de projeto (POM) e seus plugins. Quando o usuário compreende como funciona um projeto Maven, ele compreende vários, facilitando a navegação entre diversos projetos.[^1]

### Prover informações sobre o projeto com qualidade

O Maven fornece informações úteis com base no POM, incluindo:[^1]

* Changelog criado diretamente da fonte do projeto
* Referência a fontes externas
* Lista de emails controlados do projeto
* Dependências usadas pelo projeto
* Cobertura de testes de unidade

Além disso, por meio de plugins, é possível estender as informações geradas pelo Maven.

### Prover diretrizes e boas práticas de desenvolvimento

O Maven fornece boas práticas e as práticas mais atuais de várias maneiras:[^1]

* Separa em árvores diferentes o código fonte dos testes de unidade
* Cria um padrão de nomenclatura para os testes de unidade, facilitando a localização e execução dos testes
* Sugestão de layout de pastas e classes do projeto
* Gerenciamento de problemas no projeto

## Status atual do projeto

O Maven continua sendo mantido pela Apache Foundation e recebe novas versões frequentemente.[^1]

## Importância

O Maven surgiu para resolver problemas internos no desenvolvimento dos projetos da própria Apache Foundation, sendo atualmente utilizado globalmente por desenvolvedores Java para auxiliar no desenvolvimento. Segundo análise entre julho de 2022 e junho de 2023, ocorreram mais de 105 milhões de downloads.[^2]

Atualmente, é extremamente necessário o uso de algum gerenciador de projeto para o desenvolvimento, e o Maven se mostra uma opção extremamente interessante como gerenciador de projeto.

## Página oficial do projeto

* [Maven](https://maven.apache.org/)

[^1]: [Informações gerais do Maven](https://maven.apache.org/what-is-maven.html) - _Acesso em_: 29 Out. 2023
[^2]: [Número de downloads do Apache](https://dev.to/khmarbaise/analysing-download-statistics-for-apache-maven-3o4o) - _Acesso em_: 29 Out. 2023
