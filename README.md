﻿## Boas Práticas Utilizadas
 


##### Arquitetura Hexagonal:
- https://engsoftmoderna.info/artigos/arquitetura-hexagonal.html

##### Princípios SOLID: 
- https://www.freecodecamp.org/portuguese/news/os-principios-solid-da-programacao-orientada-a-objetos-explicados-em-bom-portugues/

##### Testes Unitários:
- https://jestjs.io/pt-BR/docs/getting-started

##### Banco de Dados Compartilhado:
- https://www.postgresql.org/docs/current/mvcc.html


### Iniciar a aplicação
não foi usado nest.js

#### Migrations: 
- Essa aplicacao utiliza dois banco de dados. Uma para leitura
e outro para escrita. Mais detalhes sobre no topico de boas praticas

Certifique-se de configurar corretamente as variáveis de ambiente para cada banco de dados.

- Execute as migrações do banco de dados de escrita: 
- ``` npm run typeorm:writing migration:run ```
- Execute as migrações do banco de dados de leitura:
- ``` npm run typeorm:reading migration:run ```  

#### Docker: 
Você pode iniciar a aplicação usando o Dockerfile e o docker-compose. Certifique-se de configurar corretamente as variáveis de ambiente.

#### Test
- ``` npm run test```

#### Start
- ```npm start```

