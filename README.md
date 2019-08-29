# Sistemas-Distribuidos
Repositório destinado a disciplina de Sistemas Distribuidos da Faculdade de Computação - UFU

## Entrega 0

### O Projeto

O trabalho desenvolvido consistirá em um chat em grupo, onde as pessoas terão acesso a uma sala de bate-papo e poderão receber e enviar mensagens.

As mensagens serao enviadas através de um Multicast e para que as pessoas consigam vizualiza-las, será implementado os dois protocolos TCP/IP e UDP.
O cliente enviara uma mensagem que sera recebida pelo servido e distribuida para o chat tornando-a visivel para todos os usuários na sala usando o UDP.
Para o "cadastro" de cliente na sala, como sao dados importantes a serem recebidos utilizara o TCP/IP.

Para a ordem das mensagem enviadas sera utilizado o metodo de fila, ou seja, a primeira mensagem enviada é a primeira mensagem que se recebe.

Será implementado uma maneira do usuário receber as mensagens enviadas enquanto ele estiver offline, e assim ao reconectar ele consiga ter acesso a essas mensagens.

### Os Testes

teste de concorrência: demonstrando que múltiplos clientes podem acessar o serviço ao mesmo tempo.
teste de conexão.
teste de perda de pacotes pois ha a utilização do UDP.
