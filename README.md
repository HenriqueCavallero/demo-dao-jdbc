<h1 align="center"> demo-dao-jdbc </h1>

## 😄 Sobre 
Este projeto é uma aplicação back-end focada na implementação manual do padrão DAO (Data Access Object) utilizando Java e a API JDBC.

## 📓 Descrição do Projeto
Desenvolvido durante os estudos do curso do Prof. Nélio Alves, o objetivo principal foi entender a fundo como a arquitetura DAO funciona na prática. O sistema gerencia o acesso a dados das entidades de Vendedores (`Seller`) e Departamentos (`Department`). A ideia central foi isolar as operações de banco de dados da regra de negócio, construindo toda a estrutura de mapeamento na mão, sem depender de frameworks ORM.

## ✨ Funcionalidades
- CRUD completo (Inserir, Atualizar, Deletar e Buscar)
- Tratamento de exceções personalizadas (`DbException` e `DbIntegrityException`)
- Proteção e segurança nas consultas usando `PreparedStatement`

## 🤓 Como Usar
### 1. Configure o banco de dados
Crie a base de dados `coursejdbc` no seu MySQL e execute o script SQL do projeto para gerar as tabelas.

### 2. Configure as credenciais
Abra o arquivo `db.properties` na raiz do projeto e insira o seu `user` e `password` do banco.

### 3. Execute a aplicação
Rode o programa principal através da sua IDE para testar as operações de banco de dados direto no console.

## 📦 Como Instalar 
1. Baixe ou clone este repositório.

Comando para usar no terminal para clonar o repositório:
```bash
git clone [https://github.com/HenriqueCavallero/demo-dao-jdbc.git](https://github.com/HenriqueCavallero/demo-dao-jdbc.git)
```
## 🚀 Tecnologias
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)


---
Feito por [HenriqueCavallero]
