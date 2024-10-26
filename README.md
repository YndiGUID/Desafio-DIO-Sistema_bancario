## Desafio-DIO| Criando um sistema bancário

---

# Sistema Bancário em Python

## 📖 Descrição

Bem-vindo ao **Sistema Bancário em Python**! Este projeto é uma implementação de um sistema bancário simples, desenvolvido em Python utilizando os princípios da Programação Orientada a Objetos (POO). Ele permite o gerenciamento de clientes, contas bancárias, depósitos, saques e extratos, garantindo que regras de negócio sejam seguidas, como limites diários de transações e valores máximos para saques.

## ⚙️ Funcionalidades

- **Gerenciamento de Clientes**: 
  - Cadastro e consulta de clientes pelo CPF.
  
- **Gerenciamento de Contas**:
  - Criação de contas para clientes.

- **Transações**:
  - **Depósitos**: Adicione fundos à conta.
  - **Saques**: Realize saques com limites de até R$ 500 e um máximo de 3 saques diários.
  - **Extratos**: Consulte o histórico de transações da conta.

- **Limites**:
  - Restrição de 10 transações (saques e depósitos) por dia.

## 📋 Requisitos

- Python 3.x
- Biblioteca padrão do Python

## 🚀 Instalação

Para instalar e executar este projeto em sua máquina, siga os passos abaixo:

1. **Clone o repositório**:

   ```bash
   git clone https://github.com/seu_usuario/sistema-bancario-python.git
   ```

2. **Acesse o diretório do projeto**:

   ```bash
   cd sistema-bancario-python
   ```

3. **Execute o programa**:

   ```bash
   python main.py
   ```

## 🛠️ Uso

Após executar o programa, você verá um menu interativo com as seguintes opções:

1. **Depositar**
2. **Sacar**
3. **Extrato**
4. **Criar Novo Cliente**
5. **Criar Nova Conta**
6. **Listar Contas**
7. **Sair**

Basta digitar o número da opção desejada e seguir as instruções exibidas na tela.

## 📂 Estrutura do Código

O sistema é organizado em várias classes principais:

- **Cliente**: Classe base que gerencia os dados do cliente e suas contas.
- **Conta**: Classe base para contas bancárias, que gerencia o saldo e transações.
- **ContaCorrente**: Herda de `Conta` e implementa regras específicas para contas correntes.
- **Historico**: Gerencia o histórico de transações realizadas em uma conta.
- **Transacao**: Classe abstrata para transações, como `Saque` e `Deposito`.

## 🤝 Contribuição

Contribuições são bem-vindas! Se você gostaria de melhorar este projeto, sinta-se à vontade para fazer um fork e enviar um pull request.

## 📝 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

## 📬 Contato

Para dúvidas ou sugestões, entre em contato pelo e-mail: diasingrid249@gmail.com

---
