# Log_Telegram-Mikrotik
Esse Script tem como objetivo pegar informações do log do Mikrotik " authentication failed " e mandar mensagens para telegram.

Esse script pode ser util para ficar monitorando os pppoes, caso de algum problema no mk-auth.
## Instalação

1. Só pegar o arquivo que esta acima "Log_Telegram-Mikrotik-V3.0 " e editar ele colocando seu Token e seu Chat-ID.
 
2. Só copiar e colar o script ja editado com seu Token e Chat-id em system --> Script e dar Run Script, que ele ja roda Sozinho os comandos de renomear o script1 para LogFilter, e crie agendamento.

3. Caso ocorro algum evento com " authentication failed " ele vai enviar os nomes dos pppoes com problema para Telegram.
