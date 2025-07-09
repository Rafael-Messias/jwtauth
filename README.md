# JWT Auth

Aplicação .NET Core Web Api com autenticação com Json Web Token & Refresh Tokens.

## 🚀 Funcionalidades
- Criação de usuário
- Autenticação
- Refresh Token

## 🛠️ Tecnologias Utilizadas
- .NET Core 9
- ASP.NET Core Web API
- Entity Framework Core (Code First + Migrations)
- Bootstrap
- jQuery
- PostgreSQL

## 🧱 Estrutura do Projeto
```
/JwtAuth         → Api
```

## 📦 Instalação e Execução
1. Clone o repositório
```bash
git clone https://github.com/Rafael-Messias/jwtauth.git
```

2. Configure o `appsettings.json` com sua string de conexão:
```json
"ConnectionStrings": {
  "DefaultConnection": "Host=localhost;Port=5432;Database=jwtauth;Username=postgres;Password=123456;Include Error Detail=true"
}
```

3. Migrations:
```
são executadas automaticamente pela api
```

4. Rode o projeto
```bash
dotnet run --project JwtAuth
```

5. Acesse documentação/testes via browser:
```
https://localhost:7296/scalar/v1
```

## 👨‍💻 Autor
Desenvolvido por Rafael Messias.
