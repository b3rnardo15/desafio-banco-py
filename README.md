# Sistema de Gerenciamento de Contas Bancárias

Este projeto é um sistema de gerenciamento de contas bancárias, desenvolvido como parte de um desafio na DIO (Digital Innovation One). O objetivo é permitir a criação e gerenciamento de contas para clientes, possibilitando operações como depósitos, saques e a visualização de extratos.

## Funcionalidades:

- **Cadastro de Clientes:** Permite a criação de clientes do tipo Pessoa Física, armazenando informações como nome, CPF, data de nascimento e endereço.
- **Gerenciamento de Contas:** Cada cliente pode ter múltiplas contas, todas associadas à agência fixa "0001" e com número sequencial.
- **Operações Bancárias:**
  - **Depósito:** Os clientes podem depositar valores em suas contas, com validação de valores positivos.
  - **Saque:** Permite a realização de saques, com controle de limite e saldo.
  - **Extrato:** Gera um extrato detalhado das transações realizadas, mostrando saques e depósitos, bem como o saldo atual.
- **Histórico de Transações:** Cada conta mantém um histórico de todas as transações realizadas, permitindo o rastreamento das operações.

## Estrutura do Código:

- **Classes Principais:**
  - `Cliente`: Classe base para clientes, contendo métodos para gerenciar contas.
  - `PessoaFisica`: Extende a classe `Cliente`, adicionando atributos específicos.
  - `Conta`: Classe base para contas, com métodos para depósitos, saques e histórico.
  - `ContaCorrente`: Extensão da classe `Conta`, com funcionalidades específicas para contas correntes.
  - `Transacao`: Classe abstrata que serve como base para as operações de saque e depósito.

## Como Usar:

1. Clone o repositório.
2. Execute o script Python.
3. Siga as instruções do menu para cadastrar clientes, criar contas e realizar operações bancárias.




