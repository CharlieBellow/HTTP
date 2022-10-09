# Introdução

Descrição
Existem diversos métodos HTTP, nesse módulo iremos entender os mais usados entre eles.


# Methods

Descrição
Nessa aula vamos estudar os Métodos, ou verbos do HTTP que apesar de poderem ser chamados assim não necessáriamente tem formato de verbos. Eles servem para indicar o intuito da operação que o cliente está realizando, e cada um possui seu significado, que vamos estudar nas próximas aulas. Os métodos podem ter 2 características, seguro e idempotente. Métodos seguros não alteram o servidor, são de apenas leitura, então não apresentam carga extra para o servidor e são mantidos seguros por ele, métodos considerados seguros são: GET, HEAD e OPTIONS. Os métodos Idempotentes são os métodos que não mudam de resposta, por isso a parte de "idem" no nome, mas podem ter status codes diferentes os métodos idempotentes são todos os métodos seguros, PUT e DELETE.

- Seguro: não altera o estado do servidor

- Idempotente: ao executar o método a resposta tem que ser sempre a mesma.
