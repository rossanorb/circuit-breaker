## Circuit Breaker
***
## Building e inicialização do servidor

```bash
npm run start-server

```

> este comando irá fazer o build da aplicação na pasta /build que é o que irá para produção
> e também iniciar o servidor

## Testando a aplicação
```bash
npm run test-breaker

```
> para simular respostar com falhas, dentro do index.ts existe uma função randômica que gera respostas 
> com erros 400 ou 200


## Convenções de estado
* GREEN => CLOSED
* YELLOW => HALF-OPEN
* RED => OPEN