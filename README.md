# C1
SistemaTriagem

Sistema de Triagem baseado no Questionário Washington Group
Projeto ASP.NET Core MVC para avaliar dificuldades funcionais em usuários.

Descrição

Este projeto exibe um questionário com 5 perguntas relacionadas à visão, audição, mobilidade, memória e autocuidado.

O usuário preenche o nome e seleciona o nível de dificuldade para cada pergunta.

Após enviar, o sistema calcula um resultado resumido (Sem limitações, Leve, Moderada, Severa).

O projeto utiliza ASP.NET Core MVC com Razor Views e Model Binding.


Estrutura Projecto

C1/
 ├─ Controllers/
 │    └─ TriagemController.cs   # Controller principal
 ├─ Models/
 │    └─ Avaliacao.cs           # Modelo do questionário
 ├─ Views/
 │    └─ Triagem/
 │         └─ Questionario.cshtml
 ├─ Program.cs                  # Configuração e rota padrão
 ├─ C1.csproj                   # Arquivo do projeto
 └─ README.md


Como Rodar o Projeto

Abra o terminal na pasta do projeto:

Limpe a build antiga e compile:

dotnet clean
dotnet build

Rode o projeto:

dotnet run

Abra o navegador em:

https://localhost:5162/Triagem/Questionario

A página vai abrir diretamente com o questionário.

Preencha o nome e as respostas e clique Enviar.
