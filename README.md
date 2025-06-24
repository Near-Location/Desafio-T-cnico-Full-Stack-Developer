# 🧪 Desafio Técnico – Full Stack Developer

Este projeto tem como objetivo avaliar conhecimentos em desenvolvimento full stack, com foco em autenticação, controle de acesso e gerenciamento de usuários.

---

## 📌 Desafio

Você deve implementar um sistema com as seguintes funcionalidades:

### 🎯 Funcionalidades principais

- Autenticação de usuários (login com usuário/senha)
- Controle de acesso por **perfil**
- Cadastro de usuários com os campos:
  - Nome
  - E-mail
  - CPF (formato válido e único)
  - Data de nascimento (mínimo 18 anos)
  - Data limite de acesso
  - Perfil (`ADMIN`, `VISUALIZADOR`)
  - O candidato deverá implementar todas as operações de CRUD (Criar, Ler, Atualizar, Deletar) para os usuários cadastrados.
- Usuário só pode logar se estiver dentro da data de acesso válida
- Sistema deve criar automaticamente um usuário `admin@teste.com.br` com senha `07L5s![UqI!3` na primeira execução

### 🔐 Perfis de acesso

| Perfil       | Permissões                                                         |
|--------------|---------------------------------------------------------------------|
| `ADMIN`      | Pode cadastrar, editar, deletar e visualizar usuários              |
| `VISUALIZADOR` | Pode apenas visualizar a lista e os dados dos usuários             |            

---

## ⚙️ Stack Sugerida

- **Frontend:** React + Bootstrap 5
- **Backend:** Node.js (Express, NestJS ou outro de sua preferência) Ou Java, Fique a sua escolha :)
- **Banco de dados:** PostgreSQL
- **Extras sugeridos:**
  - Autenticação via JWT
  - Docker para facilitar execução

---

## ✅ O que será avaliado

- Organização do código
- Boas práticas de segurança e validação
- Controle de acesso por perfil
- Clareza na estrutura da aplicação
- Qualidade do front-end (UX, responsividade, componentização)
- Documentação de uso no README

---

## 📤 Como Submeter o Projeto

1. **Crie um repositório no GitHub (ou outra plataforma de sua escolha)**
   - O nome do repositório pode ser algo como `auth-user-management-system` ou algo semelhante.
   
2. **Inclua uma descrição do seu projeto no README**
   - Explique brevemente o que foi feito, as tecnologias utilizadas, e como rodar o projeto.

3. **Compartilhe o link do repositório com o avaliador**
   - Após concluir o projeto, envie o link do repositório

---

## 🚀 Como rodar o projeto (sugestão)

Você pode utilizar `docker-compose` para subir o banco e o backend com facilidade.

Caso deseje, você pode incluir:
- Scripts de criação de tabelas
- Dados seed para criar o usuário `admin`

---

## 🤝 Boa sorte!

Fique à vontade para usar bibliotecas e ferramentas com as quais se sinta confortável. O importante é mostrar clareza nas decisões técnicas e atenção aos detalhes.
