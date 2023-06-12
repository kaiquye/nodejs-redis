### Teste Técnico


- Linkedin: https://www.linkedin.com/in/kaique-mendes-9b61381a5/
- Git-hub principal: https://github.com/kaiquye Fiquei sem acesso a ele durante o test. (Ja recuperei.)


Este é o README do projeto de teste técnico.

### O que falta/O que eu queria fazer
Infelizmente, não tive todos os dias disponíveis para implementar todos os recursos desejados. 
No entanto, aqui estão algumas coisas que faltam:

- Salvar a sessão do usuário com Redis: Implementar a funcionalidade de armazenar a sessão do usuário usando o Redis como um mecanismo de armazenamento de cache.
- Criar rotas de logout: Adicionar rotas e lógica para permitir que os usuários façam logout da aplicação, invalidando a sessão e removendo as informações de autenticação.
- Criar restrição de acesso baseada em Claims/Roles: Implementar uma lógica de autorização que verifica as reivindicações (claims) do usuário autenticado para permitir ou negar o acesso a determinadas partes da aplicação com base em suas permissões ou funções atribuídas.
- Testes end-to-end (2e2):



## Boas Práticas Utilizadas

##### Arquitetura Hexagonal:
- https://engsoftmoderna.info/artigos/arquitetura-hexagonal.html

##### Princípios SOLID: 
- https://www.freecodecamp.org/portuguese/news/os-principios-solid-da-programacao-orientada-a-objetos-explicados-em-bom-portugues/

##### Testes Unitários:
- https://jestjs.io/pt-BR/docs/getting-started

##### Banco de Dados Compartilhado:
- https://www.postgresql.org/docs/current/mvcc.html


### Executa a aplicacao

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
- Essa aplicacao tem apenas test unitarios, pois nao tem deu para
fazer todos o que eu queria. Tive apenas 1 final de semana disponivel.

- ``` npm run test```

#### Start
- ```npm start```

