# Log_Telegram-Mikrotik
Esse Script tem como objetivo pegar informações do log do Mikrotik " authentication failed " e mandar mensagens para telegram.

Esse script pode ser util para ficar monitorando os pppoes, caso de algum problema no mk-auth.

So pegar o arquivo que esta acima " Log_Telegram-Mikrotik " e editar ele colocando seu Token e seu Chat-ID.

Só colocar o script ja editado em system --> Scheduler e colocar para rodar a cada uns 30 segundos.

Caso ocorro algum evento com " authentication failed " ele vai enviar os nomes dos pppoes com problema.
