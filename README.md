# Projeto Acadêmico - Gestão de Alunos
Este é um projeto de aplicação Desktop desenvolvido em **C#**, utilizando o framework **.NET**. O objetivo principal do sistema é realizar o controle e gerenciamento de alunos (CRUD - Criar, Ler, Atualizar e Deletar) em um ambiente acadêmico.

## 📋 Funcionalidades
O sistema é composto pelas seguintes funcionalidades principais:

* **Controle de Alunos (`frmControleAluno`):** Interface principal para listagem e visualização dos alunos cadastrados, além de permitir a edição das informações de alunos já cadastrados.
* **Cadastro de Alunos (`frmCadastroAluno`):** Formulário para inserir novos alunos.
* **Persistência de Dados:** Integração com banco de dados para salvar as informações de forma permanente.

## 🚀 Tecnologias Utilizadas
* **Linguagem:** C#
* **Framework:** .NET Framework (v4.7.2)
* **Interface Gráfica:** Windows Forms
* **Banco de Dados:** SQL Server
* **IDE Recomendada:** Visual Studio 2019 ou superior

## 📂 Estrutura do Projeto
A estrutura de pastas do projeto está organizada da seguinte forma:

```text
projeto-academico/
├── banco/
│   └── dbAcademico.sql       # Script para criação do Banco de Dados e Tabelas
├── prjAcademico/
│   ├── Aluno.cs              # Classe de Modelo (Entidade Aluno)
│   ├── frmCadastroAluno.cs   # Lógica do formulário de cadastro
│   ├── frmControleAluno.cs   # Lógica do formulário de controle/listagem
│   ├── Program.cs            # Ponto de entrada da aplicação
│   ├── App.config            # Configurações (incluindo String de Conexão)
│   └── ...                   # Outros arquivos do projeto
