
# 🏦 Banco Cofrinho

## 📚 Sobre o projeto

O Banco Cofrinho é um projeto desenvolvido como a primeira atividade prática em dupla, com o objetivo de aplicar os conhecimentos adquiridos durante os estudos de programação em Python.

O projeto simula um sistema bancário simples através de um terminal, permitindo que o usuário realize operações financeiras básicas, como consultar saldo, depositar, sacar e visualizar o extrato bancário.

Além das funcionalidades principais, o sistema possui algumas regras adicionais de segurança e validação para tornar a experiência mais completa.

## 🎯 Objetivos

- Praticar a criação e utilização de funções em Python.
- Trabalhar com estruturas condicionais e repetição.
- Utilizar listas para armazenar movimentações financeiras.
- Implementar validações de entrada do usuário.
- Aplicar o `match case` para organizar o menu.
- Desenvolver um projeto colaborativo utilizando divisão de tarefas.

## ⚙️ Funcionalidades

- 🔐 **Acesso por senha:** exige uma senha de acesso, com limite de 3 tentativas.
- 💰 **Consulta de saldo:** exibe o saldo atual da conta.
- 📥 **Depósito:** permite adicionar dinheiro à conta, validando o valor informado.
- 📤 **Saque:** permite retirar dinheiro, respeitando o saldo disponível e o limite de R$ 1.000,00 por saque.
- 📄 **Extrato bancário:** exibe as movimentações realizadas e o saldo atual.
- 📊 **Resumo de operações:** apresenta a quantidade de depósitos e saques realizados.
- 🛡️ **Validação de entradas:** impede entradas inválidas no menu e nas operações financeiras.
- 🖥️ **Limpeza de terminal:** organiza a interface limpando a tela entre as operações.

## 🛠️ Tecnologias utilizadas

- Python 3
- Terminal / Console
- Git e GitHub

## 📋 Regras do sistema

- A senha de acesso é `1234`.
- O usuário possui até 3 tentativas para acertar a senha.
- O saldo inicial é de R$ 500,00.
- Não é permitido realizar depósitos com valores menores ou iguais a zero.
- Não é permitido realizar saques com valores menores ou iguais a zero.
- O limite máximo por saque é de R$ 1.000,00.
- Não é permitido realizar saques superiores ao saldo disponível.
- O extrato registra as operações realizadas durante a execução do programa.

## 👥 Desenvolvimento em dupla

Este projeto foi desenvolvido utilizando a metodologia de programação em dupla, com divisão de responsabilidades entre os integrantes.

### Integrante 1 — Piloto
**Rafael Sales**

Responsável pelo desenvolvimento de:

- Verificação de senha.
- Menu principal.
- Consulta de saldo.
- Operação de depósito.

### Integrante 2 — Piloto/Navegador
**Nome do integrante**

Responsável pelo desenvolvimento de:

- Operação de saque.
- Extrato bancário.
- Função principal (`Main`).
- Integração das funcionalidades do sistema.

## ▶️ Como executar

1. Certifique-se de ter o Python 3 instalado.
2. Clone este repositório ou baixe os arquivos do projeto.
3. Abra a pasta do projeto no terminal.
4. Execute o arquivo Python:

```bash
python banco_cofrinho.py
```

5. Digite a senha de acesso:

```text
1234
```

6. Escolha uma das opções disponíveis no menu.

## 📌 Menu do sistema

```text
=== BANCO COFRINHO · CAIXA ===

1 - Ver saldo
2 - Depositar
3 - Sacar
4 - Ver extrato
0 - Sair
```

## 🧠 Conteúdos praticados

Durante o desenvolvimento deste projeto, foram utilizados os seguintes conceitos:

- Variáveis.
- Tipos de dados.
- Entrada e saída de dados (`input` e `print`).
- Conversão de tipos (`int` e `float`).
- Estruturas condicionais (`if`, `elif` e `else`).
- Estruturas de repetição (`while` e `for`).
- Funções.
- Parâmetros e retornos.
- Listas.
- Tratamento de exceções (`try` e `except`).
- Método `isdigit()`.
- Método `startswith()`.
- Estrutura `match case`.
- Importação de módulos (`os`).
- Manipulação de strings.
- Formatação de valores monetários.

## 🚧 Limitações

Este projeto possui caráter exclusivamente educacional.

- Os dados não são salvos após o encerramento do programa.
- O sistema não utiliza banco de dados.
- A senha está definida diretamente no código.
- Não existe conexão com uma instituição bancária real.
- O extrato é armazenado apenas durante a execução.

## 📈 Próximos passos

Possíveis melhorias futuras para o projeto:

- Armazenar os dados em arquivos.
- Criar cadastro de usuários.
- Permitir alteração de senha.
- Implementar transferências entre contas.
- Melhorar a interface do terminal.
- Adicionar data e horário às movimentações.

## 📄 Licença

Este projeto foi desenvolvido para fins educacionais e de aprendizado em programação.

---

**Projeto acadêmico — Banco Cofrinho**  
Desenvolvido em dupla com Python 🐍
