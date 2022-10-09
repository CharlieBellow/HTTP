# Status code mais comuns

Descrição
A proposta do status code é ter uma comunicação mais clara entre o back-end com o cliente. 

Os status code do tipo 100 servem pra mostrar que a operação pode ser continuada sem problemas. 

Os status code do tipo 200 podem significar: 200 em si, significa que tudo está ok (GET e POST), 201, significa que o recurso foi criado (PUT), 204, significa que não há conteúdo (PUT e DELETE). 

Os status code do tipo 300 podem significar: 301, significa movido permanentemente, 308, significa redirecionamento permanente, 302, significa uma mudança temporária assim como o 307. 

Os status code o tipo 400 podem significar: 400, que significa que o pedido foi mal efetuado, 401, que significa que o pedido não teve autorização, 403, que significa que a autorização foi negada, 404, que o pedido não foi encontrado, 405, que significa que o método usado não é permitido e 429, que significa que foram efetuados muitos pedidos. 

Os do tipo 500: 500, que significa que ocorreu um erro desconhecido no servidor e o 503, que significa que o servidor está indisponível no momento.