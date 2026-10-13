# Calculadora OAC

Aplicação desktop desenvolvida em C# como parte de um trabalho acadêmico da disciplina de **Organização e Arquitetura de Computadores (OAC)**.

O projeto consiste em uma calculadora com interface gráfica integrada a uma implementação de operações aritméticas em **Assembly MIPS**, executada por meio do simulador MARS.

A proposta é explorar a integração entre uma aplicação desenvolvida em uma linguagem de alto nível e uma implementação em Assembly, relacionando conceitos de programação com os fundamentos da organização e arquitetura de computadores.

## 🚀 Funcionalidades

- Interface gráfica para interação com a calculadora.
- Entrada de valores e operadores aritméticos.
- Integração com a implementação em Assembly MIPS.
- Execução das operações por meio do simulador MARS.

> As funcionalidades descritas dependem da implementação disponível no projeto e da configuração correta do ambiente.

## 🛠️ Tecnologias utilizadas

- **C#** — desenvolvimento da aplicação e integração com o Assembly.
- **WPF ou Windows Forms** — construção da interface gráfica, conforme a versão utilizada.
- **Assembly MIPS** — implementação da lógica de cálculo.
- **MARS** — simulação e execução das instruções MIPS.
- **Java (JVM)** — ambiente necessário para executar o simulador MARS.

## 📂 Projetos relacionados

Este repositório contém a interface gráfica da calculadora. A implementação principal da lógica em Assembly e sua integração com o simulador estão no repositório relacionado:

- [Calculadora OAC — Assembly MIPS e integração com MARS](https://github.com/Felipesou1101/Calculadora---MARS)

## ⚙️ Requisitos

Para executar o projeto, é necessário ter:

1. Windows compatível com a aplicação.
2. SDK do .NET compatível com o framework definido no arquivo `.csproj`.
3. Java instalado e configurado no sistema.
4. Simulador MARS disponível na máquina.
5. Repositórios e arquivos necessários à integração devidamente configurados.

## ▶️ Como executar

1. Clone este repositório:

   ```bash
   git clone https://github.com/Felipesou1101/Calculadora_Interface.git
   ```

2. Clone o repositório da implementação em Assembly:

   ```bash
   git clone https://github.com/Felipesou1101/Calculadora---MARS.git
   ```

3. Configure os caminhos dos arquivos Assembly e do simulador MARS de acordo com o ambiente local.

4. Abra a solução `Calculadora_Interface.sln` no Visual Studio.

5. Verifique se as referências entre os projetos estão corretas e se todos os arquivos necessários estão disponíveis.

6. Compile e execute a aplicação pelo Visual Studio.

## 🎓 Objetivo acadêmico

O projeto foi desenvolvido para a disciplina de Organização e Arquitetura de Computadores, com o objetivo de praticar conceitos de Assembly MIPS e explorar a integração dessa linguagem com uma interface gráfica desenvolvida em C#.

## 📄 Licença

Este projeto está disponibilizado sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para obter os detalhes.
