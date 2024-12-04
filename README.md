# Projeto Loja de Games 🎮

Uma plataforma de e-commerce focada em uma loja de games, permitindo o cadastro de produtos, gerenciar o estoque de produtos, disponibilidade e separar os produtos por categorias.

## 📜 Funcionalidades Principais
- **Cadastro de Produtos:** CRUD completo para gerenciar os produtos.
- **Gestão de Estoque:** Registrar e acompanhar os produtos disponíveis na loja.
- **Catálogo de Jogos:** Gerenciamento do catálogo com jogos disponíveis para venda.

  
## 📂 Modelos de Dados

### Produtos
```
- ID (BigInt)
- nome (String)
- descricao (String)
- preco (Double)
- estoque (Integer)
- dataLancamento (LocalDate)
- status (String)
```

### Categoria
```
- ID (BigInt)
- nome (String)
- descrição (String)
```

## 💻 Tecnologias Utilizadas

Linguagem: Java 17

Framework: Spring Boot

Banco de Dados: SQL

Arquitetura: RESTful API 

## 🔧 Instalação e Configuração

1. Clone este repositório:
  ```
   git clone https://github.com/seu-repositorio/projeto_loja_games.git
  ```
2. Configure o banco de dados no arquivo `application.properties` em `src/main/resources`:
  ```
  spring.datasource.url=jdbc:mysql://localhost:3306/db_loja_games
  spring.datasource.username=seu_usuario
  spring.datasource.password=sua_senha
  ```
3. Execute o projeto:
  ```
  ./mvnw spring-boot:run
  ```

## 🛠️⌛️ Melhorias Futuras

 - Implementar autenticação e autorização.

 - Desenvolver um sistema de recomendação de jogos baseado no histórico de compras e preferências dos clientes.

 - Permitir que os usuários avaliem e escrevam comentários sobre os produtos adquiridos, melhorando a interação e confiabilidade na plataforma.

 - Criação de um Frontend para melhor interação com o usuário.


### 📝 Desenvolvido por:

- [Lucas Matheus](https://www.linkedin.com/in/lucas-matheus-lima/)
