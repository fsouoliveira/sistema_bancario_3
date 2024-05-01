# sistema_bancario_3

Esse código implementa um sistema básico de controle bancário com algumas funcionalidades principais:

1. **Menu**: Exibe um menu de opções para o usuário interagir com o sistema, incluindo depósito, saque, exibição de extrato, criação de usuário, criação de conta, listagem de contas e sair do sistema.

2. **Funções de Operações Bancárias**:
   - **Depositar**: Adiciona um valor ao saldo da conta e registra a transação no extrato.
   - **Sacar**: Retira um valor do saldo da conta, desde que as condições de saldo disponível, limite de saque e número máximo de saques não sejam excedidas. Também registra a transação no extrato.
   - **Exibir Extrato**: Mostra o extrato da conta, incluindo todas as transações realizadas e o saldo atual.
   
3. **Criação de Usuário e Conta**:
   - **Criar Usuário**: Solicita informações básicas do usuário (CPF, nome, data de nascimento e endereço) e o adiciona à lista de usuários.
   - **Criar Conta**: Associa um usuário existente a uma nova conta, fornecendo uma agência e número de conta únicos.

4. **Listagem de Contas**: Mostra as informações básicas de todas as contas cadastradas no sistema, incluindo agência, número da conta e nome do titular.

O código é estruturado em funções que são chamadas dentro de um loop principal que continua até que o usuário opte por sair do sistema. Essa estrutura facilita a manutenção e extensão do código, tornando-o modular e organizado.
