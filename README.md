## Sistema Bancário

Este é um projeto simples de sistema bancário desenvolvido em Python. O sistema permite realizar operações bancárias básicas, como depósitos, saques e consulta de extrato.

### Funcionalidades

Depósito: Permite adicionar saldo à conta bancária.

Saque: Limite de saque de R$500 por transação, podendo ser realizado no máximo 3 vezes ao dia.

Consulta de Extrato: Exibe um histórico de todas as transações realizadas.

### Tecnologias Utilizadas

Python 3.x

### Como Executar o Projeto

Clone este repositório:

git clone https://github.com/seu-usuario/sistema-bancario.git

Acesse a pasta do projeto:

cd sistema-bancario

Execute o script principal:

python sistema_bancario.py

### Como Usar

O usuário poderá realizar depósitos e saques dentro das regras estabelecidas.

O sistema bloqueará saques que ultrapassem R$500 ou que excedam o limite de 3 saques diários.

O extrato mostrará todas as transações realizadas no sistema.

### Exemplo de Uso

Bem-vindo ao Sistema Bancário!

Escolha uma opção:

d - Depositar

s - Sacar

e - Extrato

q - Sair


#### Digite a opção desejada: d

Digite o valor do depósito: 1000

Depósito realizado com sucesso!


#### Digite a opção desejada: s

Digite o valor do saque: 600

Erro! O limite de saque é R$500 por operação.


#### Digite a opção desejada: s

Digite o valor do saque: 300

Saque realizado com sucesso!


#### Digite a opção desejada: e

--- Extrato ---

Depósito: R$1000.00

Saque: R$300.00

Saldo atual: R$700.00

------Fim------

### Contribuição

Fique à vontade para contribuir com melhorias no sistema! Para isso:

Faça um fork do repositório.

Crie uma nova branch com sua funcionalidade.

Envie um pull request.

### Licença

Este projeto está sob a licença MIT. Sinta-se livre para usá-lo e modificá-lo como desejar!

Desenvolvido por andrezozzi.
