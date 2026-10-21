
# 🏦 DIO.Bank - Algoritmo de Transferência Bancária com POO em .NET

Este projeto consiste em uma aplicação de console que simula um **Sistema de Transferência Bancária**, desenvolvido como um desafio prático da **Digital Innovation One (DIO)**. 

O objetivo principal do projeto é aplicar na prática os pilares da **Programação Orientada a Objetos (POO)** em C#, criando um algoritmo estruturado para gerenciar contas de clientes, realizar saques, depósitos e transferências de forma lógica e eficiente.

---

## 🚀 Funcionalidades do Sistema

A aplicação roda diretamente no terminal (Console) e oferece um menu interativo com as seguintes opções:
* **Listar Contas**: Exibe todas as contas bancárias cadastradas no sistema.
* **Inserir Nova Conta**: Permite cadastrar uma nova conta definindo se é Pessoa Física ou Jurídica, o nome do titular, o saldo inicial e o limite de crédito.
* **Transferir Valores**: Realiza a transferência de dinheiro de uma conta de origem para uma conta de destino.
* **Sacar**: Permite efetuar saques validando se o cliente possui saldo + crédito suficiente.
* **Depositar**: Adiciona saldo a uma conta específica.
* **Limpar Tela**: Organiza o terminal para melhorar a navegação do usuário.

---

## 🧠 Conceitos de POO Aplicados

Este laboratório é ideal para consolidar conceitos essenciais do paradigma orientado a objetos, tais como:
* **Classes e Objetos**: Utilizados para modelar a entidade da conta bancária e seus comportamentos.
* **Encapsulamento**: Proteção dos dados internos da conta, permitindo alterações de saldo apenas através dos métodos validados de saque e depósito.
* **Abstração**: Representação simplificada de um cenário real de banco adaptado para um sistema de software.
* **Enumerações (Enums)**: Uso de estruturas enumeradas para definir de forma limpa o tipo de conta (Pessoa Física ou Jurídica).

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

* **C#**: Linguagem de programação utilizada para construir toda a lógica do algoritmo.
* **.NET Core (v3.1)**: Framework utilizado para a execução e compilação do projeto de console.
* **Git & GitHub**: Para controle de versão e compartilhamento do código.

---

## 📁 Estrutura do Repositório

O código está organizado de maneira limpa e modular:
* `Classes/`: Contém a classe principal (provavelmente `Conta.cs`) que encapsula os atributos do cliente (nome, saldo, crédito) e os métodos de negócio (Sacar, Depositar, Transferir).
* `Enum/`: Contém os enumeradores que ajudam na legibilidade do código (como a distinção do tipo de conta).
* `Program.cs`: O ponto de entrada da aplicação, responsável por desenhar o menu interativo no console e gerenciar o fluxo de entrada e saída de dados.

---

## ⚙️ Como Executar o Projeto Localmente

### Pré-requisitos
* [.NET Core SDK 3.1](https://microsoft.com) (ou superior) instalado na máquina.
* Um terminal de sua preferência ou uma IDE como VS Code / Visual Studio.

### Passo a Passo

1. **Clonar o repositório:**
   ```bash
   git clone https://github.com
   ```

2. **Navegar até a pasta raiz do projeto:**
   ```bash
   cd dotnet-poo-lab
   ```

3. **Restaurar as dependências (se houver):**
   ```bash
   dotnet restore
   ```

4. **Executar a aplicação:**
   ```bash
   dotnet run
   ```

Após o comando `dotnet run`, o menu interativo aparecerá no seu terminal. Basta digitar o número correspondente à ação desejada e seguir as instruções da tela!

---

## 👨‍💻 Autor

Desenvolvido por **Marcelo** (marceloxm).
Projeto de laboratório com foco educacional para fixação de lógica de programação e conceitos fundamentais de desenvolvimento de software em ambiente .NET.

