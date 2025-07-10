# MinhaApiAspNetCore

API desenvolvida durante o BootCamp WEX - End to End Engineering, utilizando ASP.NET Core, com um controller de usuário e dois métodos principais.

## Tecnologias Utilizadas

- ASP.NET Core
- C#

## Estrutura do Projeto

- `Controllers/` — Contém os controllers da API (ex: UserController)
- `Program.cs` — Configuração inicial da aplicação
- `appsettings.json` — Configurações da aplicação
- `ModuloAPI.csproj` — Arquivo de configuração do projeto

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/Fernando-A-Ferraz/MinhaApiAspNetCore.git
   ```

2. Acesse o diretório do projeto:
   ```bash
   cd MinhaApiAspNetCore
   ```

3. Execute o projeto:
   ```bash
   dotnet run
   ```

A API estará disponível em `http://localhost:5000` (ou porta configurada).

## Endpoints Principais

> Substitua abaixo pelos exemplos reais do seu controller!

### Criar Usuário

- **POST** `/api/usuario`
- **Descrição:** Cria um novo usuário.

#### Exemplo de corpo da requisição:
```json
{
  "nome": "João",
  "email": "joao@email.com"
}
```

---

### Buscar Usuário

- **GET** `/api/usuario/{id}`
- **Descrição:** Busca um usuário pelo ID.

---

