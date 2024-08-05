#Teste backend

O teste consiste em criar uma aplicação API-REST de calculos de data e valor

- Criar um endpoint que recebera data admissão e valor salarial bruto
- Validar campos (tipagem e controle de caracteres)
- Ao receber a data  e valor retornar um JSON -> exemplo ( 01/01/2021 , 5000 R$) retorna calculo de quantos dias/meses/ano até a data atual e 35% do salario bruto)
- Deve ser feito em JAVA 17 com framework springboot
- Retorno deve ser capitado em api-client (insomnia/postman/curl)
- Utilizar S.O.L.I.D, Clean Code
- Dados devem ser salvos em mongodb
- Endpoint de copnsulta aos dados salvos ( global e individual)
- Efetuar configuração docker
