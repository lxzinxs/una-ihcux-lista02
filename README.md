# 🏗️ LabDotnet: Desafio Arquiteto de Sistemas (Lista 02)

Este repositório contém o desenvolvimento de um sistema de console utilizando o ecossistema **.NET**, focado na automação de tarefas via terminal e na implementação de uma interface de linha de comando (CLI) com foco em UX/IHC.

---

## 🚀 O Desafio

O objetivo desta atividade foi abandonar a interface gráfica e construir um ambiente de desenvolvimento completo utilizando estritamente o terminal (CMD/PowerShell).

### Etapas de Construção:
1. **Preparação do Ambiente:** Criação do diretório de laboratório `LabDotnet` através do comando `mkdir`.
2. **Scaffolding:** Geração de um novo projeto de console através do comando `dotnet new console -n SistemaExpert`.
3. **Compilação e Execução:** Validação do ciclo de vida do software com os comandos `dotnet build` e `dotnet run`.
4. **Refatoração de Código:** Implementação de lógica em C# para captura de dados, cálculo de tempo de jornada e formatação de saída.

---

## ⚡ Comandos Utilizados

Além dos comandos básicos de navegação como `cd` e `dir`, foram exploradas ferramentas da CLI do .NET:

- `dotnet new console`: Cria um novo projeto de aplicação de console baseado em um template oficial.
- `dotnet build`: Compila o projeto, verificando erros de sintaxe e gerando os arquivos binários necessários.
- `dotnet run`: Compila e executa a aplicação imediatamente no terminal.
- `DateTime.Now.Year`: Propriedade utilizada no código C# para capturar o ano atual do sistema de forma dinâmica.

---

## 💻 O Código (Program.cs)

A lógica central do programa foca na interação entre o sistema e o desenvolvedor, processando o tempo de experiência:

```csharp
// Exemplo da lógica de cálculo de jornada implementada:
int anoInicio = int.Parse(entradaAno);
int anosDeJornada = DateTime.Now.Year - anoInicio;
```

---

## 📸 Evidência de Execução ("A Prova do Crime")

Abaixo, a captura de tela demonstrando o sistema sendo executado com sucesso através do terminal:

<img src="./Captura de tela 2026-03-26 195435.png" alt="Evidência do Sistema Expert .NET" width="100%">

---
**Desenvolvido por Lucas Nery Miranda** *Estudante de Ciência da Computação - UNA Contagem*
