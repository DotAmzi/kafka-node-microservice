# Microserviço com Node.js

- Utilizando Kafka;
- Utilizando Node;

## Aplicações

- API Principal; (Station);
- Geração de certificado;
-

## Fluxo

- API principal envia uma mensagem pro serviço de certificado para gerar o certificado;
- Micro-serviço de certificado devolve uma reposta (sincrona/assincrona);

Se conseguir sícrona/assíncrona:

- Receber uma resposta assíncrona de quando o e-mail com o certificado foi enviado;

## O que sabemos?

- REST (latência);
- Redis / RabbitMQ / **kafka**;

- Nubank, Uber, Paypal, Netflix;