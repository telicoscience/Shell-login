# Script de Login em Bash

Este é um script simples de tentativa de login escrito em Bash. Ele simula um processo de login onde o usuário tem até 5 tentativas para inserir o nome de usuário e senha corretos. Se o usuário digitar as credenciais corretas, o programa continua. Caso contrário, após 5 tentativas o programa será encerrado.

## Como funciona

1. O script solicita que o usuário insira um nome de usuário e senha.
2. Se os dados inseridos coincidirem com o nome de usuário (`USER`) e senha (`123`), o programa prossegue.
3. Caso contrário, o usuário tem até 5 tentativas para tentar novamente.
4. Se as 5 tentativas forem esgotadas sem sucesso, o programa é encerrado.

## Requisitos

- Ambiente Bash

## Como usar

Execute o script usando o comando:

```
./login_script.sh
```

## Exemplo de saída
```
Tentativa 1/5
Login: USER
Senha: 123
Continuando o programa...
```
Se o usuário falhar 5 vezes, a seguinte mensagem será exibida:
```
bash
Número de tentativas excedido. Parando o programa
Customização
Você pode alterar o nome de usuário e senha padrão modificando as variáveis user e pass no script.
```
