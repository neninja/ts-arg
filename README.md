# js-arg

[![emojicom](https://img.shields.io/badge/emojicom-%F0%9F%90%9B%20%F0%9F%86%95%20%F0%9F%92%AF%20%F0%9F%91%AE%20%F0%9F%86%98%20%F0%9F%92%A4-%23fff)](https://gist.github.com/nenitf/1cf5182bff009974bf436f978eea1996#emojicom)

## Setup

```sh
yarn
```

## Testes

### Criação

- `ProcedimentoUseCase.spec.ts` na pasta `usecases/**`, próximo de `ProcedimentoUseCase.ts`
- O ideal é que cada teste possua uma situação "deve acontecer x"

### Execução

```sh
# executa todos testes
yarn test

# executa teste removendo qualquer cache existente do jest
yarn test --clearCache

# executa todos testes do diretório exemplo ou exemplo.spec.js
yarn test src/path/to/exemplo
```

## Contribuindo

Veja o [CONTRIBUTING.md](CONTRIBUTING.md)
