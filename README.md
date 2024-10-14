### Teste Técnico - Backend com Node.js

#### Descrição
Você deverá criar uma API RESTful simples que simule o gerenciamento de uma pequena biblioteca. A aplicação deve permitir cadastrar livros, listar todos os livros, atualizar informações de um livro, remover um livro e detalhar um livro.

#### Requisitos Técnicos
- *Linguagem:* JavaScript
- *Framework:* Node.js com Express.js
- *Banco de Dados:* Use um banco de dados relacional (PostgreSQL ou MySQL).
- *Versionamento de Código:* Utilize Git para versionamento.
- *Requisições e Respostas:* Todas as respostas da API devem estar em formato JSON.

#### Funcionalidades

1. *Cadastrar um livro*
   - Endpoint: POST /livros
   - Dados do livro: título, autor, ano de publicação, gênero.
   - Regras:
     - Todos os campos são obrigatórios.
     - Não deve permitir o cadastro de um livro com título repetido.
   - Retorno esperado: Dados do livro criado com ID gerado pelo banco de dados.

2. *Listar todos os livros*
   - Endpoint: GET /livros
   - Deve retornar uma lista de todos os livros cadastrados.
   - Retorno esperado: Lista de livros com seus detalhes (ID, título, autor, ano de publicação, gênero).

3. *Atualizar um livro*
   - Endpoint: PUT /livros/:id
   - Permitir a atualização dos dados de um livro baseado no seu ID.
   - Regras:
     - O ID deve existir.
     - Todos os campos (título, autor, ano de publicação, gênero) podem ser atualizados.
   - Retorno esperado: Dados atualizados do livro.

4. *Deletar um livro*
   - Endpoint: DELETE /livros/:id
   - Deletar um livro pelo ID.
   - Regras:
     - O ID deve existir.
   - Retorno esperado: Mensagem de confirmação da exclusão.

5. *Detalhar um livro*
   - Endpoint: GET /livros/:id
   - Detalhar um livro pelo ID.
   - Regras:
      - O ID deve existir.
   - Retorno esperado: Dados do livro em específico.

#### Regras Adicionais
- Valide todos os dados enviados pelo usuário.
- As mensagens de erro devem ser claras e informativas (exemplo: "O título do livro já existe").

#### Bônus (não obrigatório)
- Implementar busca de livros pelo titulo.
- Implementar cadastro e login de usuários.
  
#### Entregáveis
1. Código fonte da aplicação (em um repositório Git).
2. Um arquivo README explicando como configurar e rodar o projeto.
3. Código SQL usado para criar o banco de dados, tabelas e colunas.

#### Critérios de Avaliação
- Estrutura e organização do código.
- Boas práticas de desenvolvimento (como separação de camadas: rotas, controladores, serviços).
- Uso de promessas assíncronas (async/await).
- Implementação correta dos requisitos.
- Metódos, variavéis e funções bem descritivas (nomes).

## Vídeo aula básico sobre NodeJS <a href="https://www.youtube.com/watch?v=IZRHj7givq4">link aqui</a>
  
Boa sorte!
