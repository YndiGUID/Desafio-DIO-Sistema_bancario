## Desafio-DIO| Criando um sistema bancário

# OBJETIVO GERAL
Criar um sistemas bancário na linguagem Python com as operações: Sacar, Depositar e visualizar Extrato.

## 📖 RESUMO
- Consiste em criar um sistema bancário simples na liguagem Python com 3 operações: Depósito, saque e extrato. 
- # Operação de depósito
- Deve ser possivel depósitar valores positivos na conta bancária
- Trabalhando apenas com 1 unico usuário
- Todos os depositos devem estar em uma unica variável e exibidos na operação extrato.
- # A operação saque
- O sistema tem que permitir rezlizar 3 sauqe diários com limite máximo de R$500,00 por saque.
- Caso o susuario não tenha saldo o sistema deve exibir uma mensagem informando
- Todos os saques devem ser armazernados em uma variával e ser exibido na operação extrato.
- # Operação de Extrato
- Essa operação deve listar todos depósitos e saques realizados na conta.
- no final dele deve ser exibido o saldo atual da conta.
- Se o extrato estiver em branco aparece a mensagem: "Não foram realizadas movimentaçoes"!.

 ## Sistema Bancário Python
#Descrição

Este projeto é um sistema bancário simples desenvolvido em Python, utilizando programação orientada a objetos (POO). O sistema permite o gerenciamento de clientes, contas, depósitos, saques e extratos, implementando limites diários de transações e saques.

#Funcionalidades

Gerenciamento de Clientes: Cadastro e consulta de clientes pelo CPF.
Contas Bancárias: Criação de contas para clientes.
Transações:
Depositar: Adicione fundos à conta.
Sacar: Realize saques com limites de R$ 500 e 3 saques diários.
Extrato: Consulte o histórico de transações da conta.
Limites: Restrição de 10 transações por dia (incluindo saques e depósitos).

#Requisitos

Python 3.x
Biblioteca padrão do Python
##Instalação
Para instalar e executar este projeto em sua máquina, siga os passos abaixo:

#Clone o repositório:

bash
Copiar código
git clone https://github.com/YndiGUID/Desafio-DIO-Sistema_bancario
#Acesse o diretório do projeto:

bash
Copiar código
cd sistema-bancario-python

#Execute o programa:

bash
Copiar código
python main.py

#Uso
 
 Após executar o programa, você verá um menu interativo com opções para realizar as seguintes ações:

Depositar
Sacar
Extrato
Criar novo cliente
Criar nova conta
Listar contas
Sair
Basta digitar o número da opção desejada e seguir as instruções exibidas na tela.


#Estrutura do Código
 
 O sistema é organizado em várias classes principais:

Cliente: Classe base que gerencia os dados do cliente e suas contas.
Conta: Classe base para contas bancárias, que gerencia o saldo e transações.
ContaCorrente: Herda de Conta e implementa regras específicas para contas correntes.
Historico: Gerencia o histórico de transações realizadas em uma conta.
Transacao: Classe abstrata para transações, como Saque e Deposito.
#Contribuição
Contribuições são bem-vindas! Se você gostaria de melhorar este projeto, sinta-se à vontade para fazer um fork e enviar um pull request.

#Licença

Este projeto está licenciado sob a MIT License.

Contato
Para dúvidas ou sugestões, entre em contato pelo e-mail: diasingrid249@gmail.com

     
