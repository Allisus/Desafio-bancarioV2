# Sistema Bancário

Este é um programa simples que simula um sistema bancário. O programa permite realizar operações como depósito, saque, exibir extrato, criar contas de usuários e listar contas existentes. 

## Funcionalidades

- **Depositar**: Permite realizar um depósito na conta bancária selecionada. É solicitado o valor do depósito e atualiza o saldo e o extrato da conta.
- **Sacar**: Permite realizar um saque na conta bancária selecionada. É solicitado o valor do saque e verifica se o valor é válido de acordo com o saldo disponível, o limite de saque e o número máximo de saques permitidos. Atualiza o saldo e o extrato da conta.
- **Extrato**: Exibe o extrato da conta bancária selecionada, mostrando todas as transações realizadas e o saldo atual.
- **Nova conta**: Cria uma nova conta bancária para um usuário existente. É solicitado o CPF do usuário e verifica se o usuário existe. Se existir, a conta é criada com sucesso.
- **Listar contas**: Lista todas as contas bancárias existentes, mostrando o número da agência, o número da conta e o nome do titular.
- **Novo usuário**: Cria um novo usuário para ser associado a uma conta bancária. São solicitados o CPF, nome completo, data de nascimento e endereço do usuário. O usuário é adicionado à lista de usuários existentes.
- **Sair**: Encerra o programa.

## Como executar o programa

1. Certifique-se de ter o Python instalado em seu sistema.
2. Copie o código para um arquivo com a extensão `.py`, por exemplo, `sistema_bancario.py`.
3. Abra um terminal ou prompt de comando e navegue até o diretório em que o arquivo Python foi salvo.
4. Execute o seguinte comando: `python sistema_bancario.py`.
5. O programa será iniciado e você poderá interagir com o menu para realizar as operações desejadas.

## Observações

- O código utiliza a biblioteca `textwrap` para formatar a exibição do menu e do extrato.
- O programa armazena os dados em variáveis na memória durante a execução. Não há persistência dos dados após encerrar o programa.
- O programa permite criar contas apenas para usuários já existentes. Não é possível criar um usuário durante a criação de uma conta.
- O número da agência é fixo como "0001" e o número da conta é gerado automaticamente incrementando-se o número de contas existentes.
- O limite de saques é definido como 3 e o limite de saque por transação é definido como 500.