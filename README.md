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
  - CPF (formato válido e único)
  - Data de nascimento (mínimo 18 anos)
  - Data limite de acesso
  - Perfil (`ADMIN`, `VISUALIZADOR`, `USER`)
- Usuário só pode logar se estiver dentro da data de acesso válida
- Sistema deve criar automaticamente um usuário `admin` com senha `admin` na primeira execução

### 🔐 Perfis de acesso

| Perfil       | Permissões                                                         |
|--------------|---------------------------------------------------------------------|
| `ADMIN`      | Pode cadastrar, editar, deletar e visualizar usuários              |
| `VISUALIZADOR` | Pode apenas visualizar a lista e os dados dos usuários             |
| `USER`       | Personalize como preferir, se necessário                           |

---

## ⚙️ Stack Sugerida

- **Frontend:** React + Bootstrap 5
- **Backend:** Node.js (Express, NestJS ou outro de sua preferência)
- **Banco de dados:** PostgreSQL
- **Extras sugeridos:**
  - Autenticação via JWT
  - Docker para facilitar execução
  - Testes automatizados com Jest, Mocha ou JUnit

---

## ✅ O que será avaliado

- Organização do código
- Boas práticas de segurança e validação
- Controle de acesso por perfil
- Clareza na estrutura da aplicação
- Qualidade do front-end (UX, responsividade, componentização)
- Testes básicos automatizados (login e cadastro)
- Documentação de uso no README

---

## 🚀 Como rodar o projeto (sugestão)

Você pode utilizar `docker-compose` para subir o banco e o backend com facilidade.

Caso deseje, você pode incluir:
- Scripts de criação de tabelas
- Dados seed para criar o usuário `admin`

---

## 🤝 Boa sorte!

Fique à vontade para usar bibliotecas e ferramentas com as quais se sinta confortável. O importante é mostrar clareza nas decisões técnicas e atenção aos detalhes.
