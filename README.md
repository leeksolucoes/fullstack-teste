# Teste Leek Soluções: Vaga Desenvolvedor Fullstack Pleno

Segue abaixo as instruções para a execução do teste.

---

### Instruções

1. **Faça um fork desse projeto** para a sua conta pessoal do GitHub.
2. **Desenvolva a aplicação** conforme as Especificações Técnicas abaixo.
3. **Crie um README** com as instruções para compilar, testar e rodar o projeto.
4. O link do repositório deverá ser enviado para o e-mail **gabriel@leeksolucoes.com.br** com o título **Teste Vaga Fullstack**.

---

### Especificações Técnicas

#### Funcionalidades

1. **Autenticação de Usuário**

   - Permitir que o usuário se registre e faça login usando autenticação JWT.
   - Proteger rotas para que apenas usuários autenticados possam acessar a aplicação.

2. **CRUD de Tarefas**

   - O usuário autenticado deve poder criar, visualizar, atualizar e excluir tarefas.
   - Cada tarefa deve ter:
     - Título
     - Descrição
     - Status (ex.: "pendente", "em progresso", "concluída")
     - Datas de criação e conclusão (opcional)

3. **Interface de Usuário**
   - Criar uma interface com:
     - Tela de login e registro
     - Tela de listagem e gerenciamento de tarefas
     - Modal de confirmação para remoção de tarefa
   - Aplicar um design básico e responsivo

#### Requisitos Técnicos

1. **Front-end**: Desenvolver em **Next.js**.
   - Implementar rotas protegidas e controle de autenticação.
   - Estilizar com CSS ou qualquer pré-processador.
2. **Back-end**: Desenvolver em **NestJS**.
   - Implementar rotas REST para gerenciar as tarefas e autenticação.
   - Utilizar **Prisma** ou **TypeORM** para gerenciar o banco de dados relacional.
3. **Banco de Dados**
   - Configurar um banco de dados relacional **PostgreSQL**.
4. **Validação e Boas Práticas**
   - Implementar validação dos dados (como uso de class-validator para validações no NestJS).
   - Proteger rotas de back-end usando middlewares de autenticação.

---

### Pontos Extras

- Dockerização.
- Criar uma documentação da api com **Swagger**.

---

### O que avaliaremos em seu teste

1. **Organização do Projeto**
2. **Qualidade e Estrutura do Código**
3. **Componentização e Lógica**
4. **Alcance dos Objetivos Propostos**
5. **Atenção aos Detalhes e Boas Práticas**

---

Boa sorte! 😉
