# Imersão Dev Back-End | Alura

Bem-vindo ao projeto **Imersão Dev Back-End**, desenvolvido como parte do curso de Imersão Dev Back-End da Alura! Este repositório contém uma aplicação back-end criada com foco em conceitos fundamentais e implementação prática de programação no lado do servidor.

🌐 **[Link do Curso](https://cursos.alura.com.br/imersao)**

---

## ✨ Visão Geral do Projeto

Este projeto foi criado para:
- Construir e implementar uma aplicação funcional no back-end.
- Aplicar conceitos-chave do back-end, incluindo roteamento, middleware e interação com banco de dados.
- Utilizar ferramentas como Postman para testar rotas e verificar funcionalidades.

## 🚀 Tecnologias Utilizadas

As seguintes tecnologias foram empregadas no desenvolvimento deste projeto back-end:

- **Node.js**: Ambiente de execução de JavaScript para construção da aplicação.
- **Express.js**: Framework que simplifica o gerenciamento de rotas e middleware.
- **Postman**: Ferramenta externa utilizada para testar e verificar os endpoints da API.
- **Mongoose**: Para modelagem de dados e interação com o MongoDB.
- **Dotenv**: Gerenciamento seguro de variáveis de ambiente.
- **Nodemon**: Facilitador do desenvolvimento, reiniciando automaticamente o servidor ao salvar mudanças no código.

## 📂 Estrutura do Projeto

ImersaoBackEnd-main/
├── src/
│   ├── config/       # Arquivos de configuração (ex.: conexão com banco de dados)
│   ├── controllers/  # Controladores que gerenciam a lógica da aplicação
│   ├── models/       # Modelos de dados para MongoDB utilizando Mongoose
│   ├── routes/       # Definições de rotas da aplicação
│   ├── services/     # Serviços principais com a lógica de negócios
├── server.js         # Ponto de entrada principal do servidor
├── package.json      # Dependências e scripts
├── uploads/          # Armazenamento de arquivos enviados

## 🛠️ Principais Funcionalidades

1. **Roteamento**: Rotas personalizadas para lidar com diferentes endpoints da API.
2. **Middleware**: Inclui middleware para processamento de requisições.
3. **Interação com Banco de Dados**: Utiliza MongoDB para persistência de dados via Mongoose.
4. **Testes**: Rotas testadas com Postman para garantir confiabilidade da API.
