# Chat 'event-driven' utilizando WebSocket com PHP

## Comandos para executar a aplicação

1) Instale as dependências
```
composer install
```

2) Rode o servidor
```
php bin/chat-server.php
```

3) Conecte várias instâncias do terminal no servidor, via Telnet
```
telnet localhost 8080
```
Caso queira, pode subsituir ``localhost`` pelos ``seu ip``, no caso de acessar o servidor em outros computadores.

4) Digite a mensagem e dê enter

As mensagens serão enviadas para todos os dispositivos conectados no servidor.
