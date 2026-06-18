# 🗄️ SQL - Estudos e Testes

Repositório dedicado à inicialização e entendimento de **Banco de Dados SQL**, incluindo testes rápidos, scripts e queries.

---

## 📁 Conteúdo

- Testes rápidos de conceitos SQL
- Scripts de criação e manipulação de tabelas
- Queries de consulta, inserção, atualização e exclusão
- Exemplos práticos baseados em projetos reais

---

## 💊 Projeto de Referência — Controle de Medicamentos

Desenvolvido durante o curso Fullstack da [Academia do Programador](https://www.academiadoprogramador.net) 2026.

Um sistema de controle de medicamentos com os seguintes módulos:

| Módulo | Descrição |
|---|---|
| Fornecedores | Cadastro com CNPJ único |
| Pacientes | Cadastro com CPF e Cartão do SUS únicos |
| Medicamentos | Controle de estoque com alerta de baixa quantidade |
| Funcionários | Cadastro com CPF único |
| Estoque | Requisições de entrada e saída com atualização automática |

---

## 🚀 Como executar o projeto de referência

```bash
# Restaurar dependências
dotnet restore

# Executar
dotnet run --project ControleDeMedicamentosWeb.WebApp
```

**Requisito:** .NET 10.0 SDK
