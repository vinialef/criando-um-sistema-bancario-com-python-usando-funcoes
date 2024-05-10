# Sistema Bancário Simples Usando Funções em Python

Este repositório contém a implementação de um sistema bancário simples em Python. O sistema permite que os usuários realizem diversas operações bancárias, como depositar fundos, sacar fundos, visualizar extratos de conta, criar novas contas, listar contas existentes e cadastrar novos usuários.

## Funcionalidades
- **Depositar**: Os usuários podem depositar fundos em suas contas.
- **Sacar**: Os usuários podem sacar fundos de suas contas, levando em consideração o saldo da conta e os limites de saque.
- **Extrato de Conta**: Os usuários podem visualizar o extrato de suas contas, incluindo o histórico de transações.
- **Criar Conta**: Novas contas podem ser criadas e associadas a usuários existentes.
- **Listar Contas**: As contas existentes podem ser listadas, exibindo detalhes da conta e as informações do usuário associado.
- **Cadastrar Usuário**: Novos usuários podem ser cadastrados com suas informações pessoais.
- **Interface de Menu**: O sistema fornece uma interface simples baseada em menu para os usuários interagirem.

## Como usar?
1. **Clonar Repositório**: Baixe ou clone este repositório em sua máquina local.

2. **Execute o Programa**: Execute o script Python `Criando um Sistema Bancário com Python Usando Funções.py`


3. **Seguir as Instruções do Menu**: Siga as instruções do menu exibidas no console para realizar várias operações bancárias.

## Exemplo de Uso

```

    ================ MENU ================
    [1]Depositar
    [2]Sacar
    [3]Extrato
    [4]Nova conta
    [5]Listar contas
    [6]Novo usuário
    [7]Sair
    => 6
Digite seu cpf aqui (somente os 11 números): 16824783005
Digite o nome completo: Luan Vitor Ramos
Digite a data de nascimento aqui (DD/MM/AA): 25/04/1994
Digite seu endereço aqui(Rua - Número - Bairro - Cidade/Sigla do Estado): Rua Alfredo Duarte Filho - 686 - Jardim São Paulo - Recife/PE

====Usuário cadastrado com sucesso!====


    ================ MENU ================
    [1]Depositar
    [2]Sacar
    [3]Extrato
    [4]Nova conta
    [5]Listar contas
    [6]Novo usuário
    [7]Sair
    => 4
Informe o CPF do usuário: 16824783005

=== Conta criada com sucesso! ===


    ================ MENU ================
    [1]Depositar
    [2]Sacar
    [3]Extrato
    [4]Nova conta
    [5]Listar contas
    [6]Novo usuário
    [7]Sair
    => 5
====================================================================================================
            Agência: 0001
            C/C: 1
            Titular: Luan Vitor Ramos



    ================ MENU ================
    [1]Depositar
    [2]Sacar
    [3]Extrato
    [4]Nova conta
    [5]Listar contas
    [6]Novo usuário
    [7]Sair
    => 1
Informe o valor do depósito: 293
Depósito realizado com sucesso!


    ================ MENU ================
    [1]Depositar
    [2]Sacar
    [3]Extrato
    [4]Nova conta
    [5]Listar contas
    [6]Novo usuário
    [7]Sair
    => 2
Informe o valor do saque: 174
Saque concluído!



    ================ MENU ================
    [1]Depositar
    [2]Sacar
    [3]Extrato
    [4]Nova conta
    [5]Listar contas
    [6]Novo usuário
    [7]Sair
    => 1
Informe o valor do depósito: 149
Depósito realizado com sucesso!


    ================ MENU ================
    [1]Depositar
    [2]Sacar
    [3]Extrato
    [4]Nova conta
    [5]Listar contas
    [6]Novo usuário
    [7]Sair
    => 2
Informe o valor do saque: 97
Saque concluído!



    ================ MENU ================
    [1]Depositar
    [2]Sacar
    [3]Extrato
    [4]Nova conta
    [5]Listar contas
    [6]Novo usuário
    [7]Sair
    => 1
Informe o valor do depósito: 687
Depósito realizado com sucesso!


    ================ MENU ================
    [1]Depositar
    [2]Sacar
    [3]Extrato
    [4]Nova conta
    [5]Listar contas
    [6]Novo usuário
    [7]Sair
    => 2
Informe o valor do saque: 567
Falha na operação! Limite de crédito excedido



    ================ MENU ================
    [1]Depositar
    [2]Sacar
    [3]Extrato
    [4]Nova conta
    [5]Listar contas
    [6]Novo usuário
    [7]Sair
    => 2
Informe o valor do saque: 456
Saque concluído!



    ================ MENU ================
    [1]Depositar
    [2]Sacar
    [3]Extrato
    [4]Nova conta
    [5]Listar contas
    [6]Novo usuário
    [7]Sair
    => 1
Informe o valor do depósito: 76
Depósito realizado com sucesso!


    ================ MENU ================
    [1]Depositar
    [2]Sacar
    [3]Extrato
    [4]Nova conta
    [5]Listar contas
    [6]Novo usuário
    [7]Sair
    => 2
Informe o valor do saque: 127
Saque concluído!



    ================ MENU ================
    [1]Depositar
    [2]Sacar
    [3]Extrato
    [4]Nova conta
    [5]Listar contas
    [6]Novo usuário
    [7]Sair
    => 3

=========EXTRATO==========
Depósito: R$ 293.00
Saque: R$ 174.00
Depósito: R$ 149.00
Saque: R$ 97.00
Depósito: R$ 687.00
Saque: R$ 456.00
Depósito: R$ 76.00
Saque: R$ 127.00


==========================
Saldo total:R$ 351.00

==========================


    ================ MENU ================
    [1]Depositar
    [2]Sacar
    [3]Extrato
    [4]Nova conta
    [5]Listar contas
    [6]Novo usuário
    [7]Sair
    =>
