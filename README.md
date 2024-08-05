# Teste Backend / TechLead


# Desenvolvedor Pleno

O teste consiste em criar uma aplicação API-REST para cálculos de data e valor utilizando Java na versão 17 ou superior com o framework Spring Boot. O objetivo é desenvolver um endpoint que receba a data de admissão e o valor salarial bruto, realizando as seguintes tarefas.

    - Validação de Campos: Implementar validações para garantir a tipagem correta e o controle de caracteres dos campos recebidos.
    - Cálculo e Retorno: Ao receber a data e o valor, o endpoint deve retornar um JSON com:
        - Cálculo de quantos dias, meses e anos se passaram até a data atual.
        - 35% do salário bruto.
    - Persistência de Dados: Os dados devem ser salvos em um banco de dados MongoDB.
    - Consultas: Criar um endpoint para consulta dos dados salvos, permitindo acesso global e individual.
    - Documentação: O retorno deve ser testado e validado utilizando ferramentas como Insomnia, Postman ou Curl.
    - Configuração Docker: O projeto deve ser configurado para rodar em um ambiente Docker, incluindo um Dockerfile e um docker-compose.yml para facilitar a orquestração.
    - Documentação com OpenAPI: Implementar a documentação da API utilizando a especificação OpenAPI, permitindo que outros desenvolvedores visualizem e testem os endpoints de forma interativa.
    - Controller Advice: Implementar um Controller Advice para tratamento de erros, garantindo que exceções sejam capturadas e retornadas em um formato JSON consistente.

Requisitos Técnicos.

    - Conhecimento em princípios S.O.L.I.D e Clean Code.
    - Experiência com Spring Boot e MongoDB.
    - Habilidade em criar e testar APIs REST.



# Desenvolvedor Sênior 
   
O teste consiste em desenvolver uma aplicação API-REST robusta e escalável para cálculos de data e valor, utilizando Java na versão 17 ou superior com o framework Spring Boot. O objetivo é criar um endpoint que receba a data de admissão e o valor salarial bruto, com as seguintes especificações.

    - Validação de Campos: Implementar uma validação rigorosa para garantir a tipagem correta e o controle de caracteres, utilizando anotações de validação do Spring.
    - Cálculo e Retorno: O endpoint deve retornar um JSON que inclua:
        - Cálculo detalhado de quantos dias, meses e anos se passaram até a data atual, utilizando uma abordagem orientada a objetos.
        - Cálculo de 35% do salário bruto, com considerações sobre possíveis erros de cálculo.
    - Persistência de Dados: Utilizar MongoDB para salvar os dados, garantindo que a estrutura de dados siga os princípios de design de banco de dados.
    - Consultas: Criar endpoints RESTful para consulta dos dados salvos, permitindo acesso global e individual, com suporte a filtros e paginação.
    - Documentação e Testes: O retorno deve ser validado utilizando Insomnia, Postman ou Curl. 
    - Implementar testes automatizados (unitários e de integração) para garantir a qualidade do código.
    - Configuração Docker: O projeto deve ser configurado para rodar em um ambiente Docker, incluindo um Dockerfile e um docker-compose.yml para facilitar a orquestração.
    - Documentação com OpenAPI: Criar uma documentação detalhada utilizando a especificação OpenAPI, garantindo que todos os endpoints, parâmetros e respostas sejam bem descritos. Isso deve incluir exemplos de requisições e respostas, facilitando o uso da API por outros desenvolvedores.
    - Controller Advice: Implementar um Controller Advice para tratamento de erros, garantindo que exceções sejam capturadas e retornadas em um formato JSON consistente e informativo, seguindo as melhores práticas de tratamento de erros.

Requisitos Técnicos.

    - Domínio de princípios S.O.L.I.D e Clean Code, aplicando-os em todos os aspectos do desenvolvimento.
    - Experiência avançada com Spring Boot e MongoDB.
    - Capacidade de projetar e implementar APIs REST escaláveis e seguras.
    - Habilidade em realizar code reviews e mentorias para desenvolvedores menos experientes.

# Tech Lead

Desenvolvimento de uma API-REST e Integração com Next.js

O desafio consiste em criar uma aplicação API-REST para cálculos de data e valor utilizando Java na versão 17 ou superior com o framework Spring Boot e uma API em Next.js para interface do usuário. O objetivo é desenvolver um endpoint que receba a data de admissão,o valor salarial bruto e cep. As tarefas a serem realizadas incluem.

    * Validação de Campos: Implementar validações rigorosas para garantir a tipagem correta e o controle de caracteres dos campos recebidos.
    * Cálculo e Retorno: Ao receber a data e o valor, o endpoint deve retornar um JSON com:
        ◦ Cálculo de quantos dias, meses e anos se passaram até a data atual.
        ◦ 35% do salário bruto.
        - Dados completos do cep
    * Chamada Externa: Realizar uma chamada à API do ViaCEP para obter informações de endereço com base no CEP fornecido pelo usuário.
    * Persistência de Dados: Os dados devem ser salvos em um banco de dados MongoDB.
    * Consultas: Criar endpoints RESTful para consulta dos dados salvos, permitindo acesso global e individual, com suporte a filtros e paginação.
    * Documentação e Testes: O retorno deve ser validado utilizando Insomnia, Postman ou Curl. 
    * Implementar testes automatizados (unitários e de integração) para garantir a qualidade do código.
    * Configuração Docker: O projeto deve ser configurado para rodar em um ambiente Docker, incluindo um Dockerfile e um docker-compose.yml para facilitar a orquestração.
    * Documentação com OpenAPI: Criar uma documentação detalhada utilizando a especificação OpenAPI, garantindo que todos os endpoints, parâmetros e respostas sejam bem descritos, incluindo exemplos de requisições e respostas.
    * Controller Advice: Implementar um Controller Advice para tratamento de erros, garantindo que exceções sejam capturadas e retornadas em um formato JSON consistente e informativo.
    * API em Next.js: Criar uma aplicação em Next.js que consuma a API desenvolvida em Spring Boot, permitindo que os usuários insiram a data de admissão, o valor salarial bruto e o CEP, exibindo os resultados de forma amigável.

Requisitos Técnicos.

    * Domínio de princípios S.O.L.I.D e Clean Code, aplicando-os em todos os aspectos do desenvolvimento.
    * Experiência avançada com Spring Boot, MongoDB e Next.js.
    * Capacidade de projetar e implementar APIs REST escaláveis e seguras.
    * Habilidade em realizar code reviews e mentorias para desenvolvedores menos experientes.

Dicas para o Candidato.

    * Organize seu tempo: divida a hora em partes para cada tarefa.
    * Foque na qualidade do código e na documentação.
    * Considere a arquitetura da aplicação e como os componentes se comunicam.
    * Teste as chamadas externas e a integração entre a API e o Next.js.
    * Caso tenha algum tratamento a acrescentar na API, isso será avaliado também.


