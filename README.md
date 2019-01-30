# Design Tokens

Exemplo de projeto para integrar Tokens de Design usando [theo](https://github.com/salesforce-ux/theo).

## Início

```bash
$ git clone https://github.com/guigonzalez/designtokens.git
$ cd designtokens
$ npm install
```

## Desenvolvimento

Ao desenvolver seu website com tokens de design use `npm run dev`
e depois abra em [localhost:3000](http://localhost:3000).

Agora você pode começar a editar o seu `src/index.html` e `src/styles/main.scss`.

Para ver os documentos gerados pelos seus tokens de design, acesse [localhost:3000/generated/app.html](http://localhost:3000/generated/app.html).
Nota: Você pode alterar seus tokens de design `./design-tokens/app.json` ou `./design-tokens/aliases.json` e ver mudanças em tempo real no seu site.

Você também pode usar Design Tokens na linguagem YAML, basta converter os arquivos de código neste site: [http://convertjson.com/yaml-to-json.html].

Além disso, se você abrir [localhost:3000](http://localhost:3000) e mudar os Tokens de Design,
as atualizações são refletidas também em tempo real.
