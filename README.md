# Sistema Bancário em Python
### Parte do desafio de Códigos da plataforma DIO.

Este é um sistema bancário simples desenvolvido em Python com geração de Logs e Persistência de dados na memória.

Foram implementadas as ações fundamentais de um sistema bancário.

## Dependências do Projeto

Este projeto foi desenvolvido em Python 3.12.6 e não requer a instalação de pacotes externos. Basta ter o Python 3.x ou versão superior instalada no seu ambiente para executá-lo corretamente.

Apenas bibliotecas padrão disponíveis nativamente em qualquer instalação do Python 3.x foram utilizadas.

## Ações Possíveis no Sistema

1. **Criar usuário:** Permite registrar um novo cliente/ usuário com informações básicas como CPF, nome, data de nascimento e endereço.
2. **Criar conta:** Associa uma conta bancária a um cliente existente, definindo limites de saque e transações.
3. **Depositar:** Permite realizar depósitos em uma conta.
4. **Sacar:** Permite realizar saques de uma conta, respeitando limites de saldo e número de transações diárias.
5. **Exibir extrato:** Mostra o histórico de transações de uma conta específica, bem como o saldo atual.
6. **Listar contas:** Exibe todas as contas registradas no sistema.
7. **Sair:** Encerra o programa.

## Passos para Sacar/Depositar no Sistema

### Criar Conta
1. Para criar uma conta é necessário criar um usuário primeiro.

### Sacar
1. Selecione a opção `S` no menu principal para realizar um saque.
2. Informe o CPF do cliente.
3. Se o cliente e a conta forem encontrados:
   - Insira o valor que deseja sacar.
   - O sistema verificará o saldo disponível, os limites de saque e o número de saques permitidos por dia.
   - Se todos os critérios forem atendidos, o saque será realizado com sucesso e o saldo será atualizado.

### Depositar
1. Selecione a opção `D` no menu principal para realizar um depósito.
2. Informe o CPF do cliente.
3. Se o cliente e a conta forem encontrados:
   - Insira o valor que deseja depositar.
   - O sistema verificará se o valor é válido (positivo).
   - O depósito será realizado com sucesso e o saldo será atualizado.

## Como Executar o Sistema

1. Certifique-se de que o Python 3.x está instalado no seu computador.
2. Execute o arquivo `sistema-bancario.py` em um terminal ou IDE.
   ```bash
   python sistema-bancario.py
   ```
3. Interaja com o menu para realizar as ações desejadas.
