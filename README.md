# 🛒 ShopEasy  

**ShopEasy** é um projeto de E-commerce desenvolvido em .NET 9 com uma estrutura baseada no padrão **Domain-Driven Design (DDD)**. O objetivo é criar uma aplicação escalável, modular e de fácil manutenção, que sirva tanto como uma solução prática quanto como um modelo para desenvolvedores interessados em aprender boas práticas de desenvolvimento.  

## 🚀 Tecnologias Utilizadas  

- **.NET 9**  
- **Swagger** (para documentação de APIs)  
- **DDD (Domain-Driven Design)**  
- **Camadas do Projeto**:  
  - API  
  - Aplicacao  
  - DataTransfer (DTOs)  
  - Dominio  
  - DominioTestes  
  - Infra  
  - Workers  
  - Job  

## 🌟 Funcionalidades Planejadas  

1. Gerenciamento de produtos.  
2. Cadastro e autenticação de usuários.  
3. Carrinho de compras.  
4. Pagamentos online.  
5. Sistema de pedidos e acompanhamento.  

## 📁 Estrutura do Projeto  

```plaintext  
ShopEasy/  
├── API/            # Camada de apresentação e endpoints REST.  
├── Aplicacao/      # Lógica de aplicação e coordenação de casos de uso.  
├── DataTransfer/   # DTOs para transferência de dados.  
├── Dominio/        # Entidades e regras de negócio.  
├── DominioTestes/  # Testes unitários do domínio.  
├── Infra/          # Implementação de repositórios e comunicação com a base de dados.  
├── Workers/        # Processamento de tarefas em background.  
└── Job/            # Tarefas agendadas e automações.  
```  

## 📚 Como Executar  

1. Clone este repositório:  
   ```bash  
   https://github.com/GabrielCezario1/ShopEasy.git
   ```  
2. Acesse a pasta do projeto:  
   ```bash  
   cd shopeasy  
   ```  
3. Restaure os pacotes NuGet:  
   ```bash  
   dotnet restore  
   ```  
4. Execute a aplicação:  
   ```bash  
   dotnet run --project API  
   ```  
5. Acesse o Swagger para explorar os endpoints:  
   - URL: `http://localhost:5000/swagger`  

## 🛠️ Contribuindo  

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues, sugerir melhorias ou enviar pull requests.  


## 🌐 Contato  

Gabriel Vieira  
[LinkedIn]([https://www.linkedin.com/in/seu-usuario](https://www.linkedin.com/in/gabriel-vieira-4443ba109/))  
