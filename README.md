# Problema

Precisamos criar uma mecanica para nos ajudar em procedimentos de combate a fraude, para isso foi criado uma base de dados com uma relação de CPFs cujo cadastro deverá ser negado caso um determinado usuário tente aplicar para uma das oportunidades disponíveis na plataforma.

Para atender essa demanda, iremos criar um aplicação web (PWA) que avalia se o CPF informado aparece na lista de negação enquanto o cadastro é realizado.

# Requisitos

- CRUD para manipulação da lista de usuários
    - Um modelo com identificador, nome, e-mail e CPF
        - O identificador deve ser do tipo UUID
        - Nome deve possuir _nome_ e _sobrenome_ obrigatoriamente
        - E-mail precisa ser um e-mail válido
        - O número do documento precisa ser um número válido
- Carga de uma [lista](deny.txt) pré-definida de documentos com restrição
- Caso o usuário apareça na lista de negação, uma mensagem adequada deve ser exibida
- Os dados não devem ser persistidos, exceto no `store` em memória.
- Instruções para execução do projeto

# Premissas

A aplicação deve ser escrita usando Vue, Vue X e Vue Router

# Extras

- Testes
- Typescript
- Docker para criação da infraestrutura
- Checagem de código usando linter e/ou formatadores
