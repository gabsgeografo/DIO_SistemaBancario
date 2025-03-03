# DIO_SistemaBancario
Desafio de Projeto do Bootcamp DIO que consiste na criação de um Sistema Bancário em Linguagem Python

<div align="center">
<img src="https://assets.dio.me/wqFNFD1_7AKN1MpbZvurY1cUcpUXQ2ELMfW5Bi9R8VM/f:webp/h:120/q:80/L3RyYWNrcy9lN2MzZjVkNy0yMTEwLTQ3N2YtYmYxMS0wNjg3MjQzMjZjYzEucG5n" alt="Logo Bootcamp" width="80">
<h1>DIO BOOTCAMP</h1>
<img src="https://assets.dio.me/wqFNFD1_7AKN1MpbZvurY1cUcpUXQ2ELMfW5Bi9R8VM/f:webp/h:120/q:80/L3RyYWNrcy9lN2MzZjVkNy0yMTEwLTQ3N2YtYmYxMS0wNjg3MjQzMjZjYzEucG5n" alt="Logo Bootcamp" width="220">
</div>

#  :bank: Desafio: Otimizando o Sistema Bancário com Funções Python


## :memo: Objetivo do Desafio
Separar as funcões existentes de saque, depósito e extrato em
funcões. Criar duas novas funcões: cadastrar usuário (cliente) e cadastrar conta bancária.

## :punch: Desafio
Precisamos deixar nosso código modularizado, para isso iremos criar funções para as operações existentes: sacar,
depositar e visualizar histórico. Além disso, para a nova versão do nosso sistema precisamos criar duas novas funções: criar
usuário (cliente) e criar conta corrente (vincular com usuário).

## :knife: Separação em Funções
Vamos criar funções para todas as operações do sistema. Para exercitar tudo o que foi aprendido neste módulo, cada
função vai ter uma regra na passagem de argumentos. O retorno e a forma como serão chamadas, pode ser definida pelo programador 
da forma que achar mais conveniente.

## :heavy_minus_sign: Saque
A função saque deve receber os argumentos apenas por nome (keyword only). 
Sugestão de argumentos: saldo, valor, extrato, limite, número_saques, limite_saques. Sugestão de retorno: saldo e extrato.

## :heavy_plus_sign: Depósito
A função depósito deve receber os argumentos apenas por posição (positional only). Sugestão de argumentos: saldo, valor, extrato. Sugestão de retorno: saldo e extrato.

## :tomato:	Extrato
A função extrato deve receber os argumentos por posição e nome (positional only e keyword only). Argumentos posicionais: saldo, argumentos nomeados: extrato.

## :new: Novas funções
Criaremos duas novas funções: criar usuário e criar conta corrente. 

## :bust_in_silhouette: Criar usuário (cliente)
O programa deve armazenar os usuários em uma lista, um usuário é composto por: nome, data de nascimento, cpf e
endereço. O endereço é uma string com o formato: logradouro, numero - bairro - cidade/sigla estado. Deve ser armazenado
somente os números do CPF. Não será possível criar 2 usuários com o mesmo CPF.

## :money_with_wings: Criar conta corrente
O programa deve armazenar contas em uma lista, uma conta é composta por: agência, número da conta e usuário. O número
da conta é sequencial, iniciando em `1`. O número da agência é fixo: `0001`. O usuário pode ter mais de uma conta, mas uma
conta pertence a somente um usuário.

<br>

> [!NOTE]
> Para vincular um usuário a uma conta, filtre a lista de usuários buscando o número do CPF informado para cada usuário da lista.

<br>
