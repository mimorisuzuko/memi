# Memi

忘れないうちにREADMEだけ書いておく．
Makefileよく分からないからNode.jsで書きたい．けど，package.jsonを生成してnpm scriptsを書くのはウザい．
代案知りたい．

## Memifile

```js
const anyFunc = require('any-func');

export default {
  clean: () => {
    console.log('cleanしたお');
  },
  build: () => {
    console.log('buildしたお');
  },
  yo: (...args) => {
    anyFunc(...args);
  }
};

```

## Usage

```zsh
memi clean
# say "cleanしたお"
```

## めもり

- `~/.memi/` に `node_modules` を格納する
  - `~/.memi/` で `Memifile` を持ってきて実行するようにする

## 柿崎芽実

![](http://cdn.keyakizaka46.com/images/14/c34/6ca0737dca69cfab05b2861820cf2/400_320_102400.jpg)
