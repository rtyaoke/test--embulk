

#

## install plugins

```command prompt
embulk gem install embulk-input-sqlserver
embulk gem install embulk-output-postgresql
```



digdag run allsheet.dig

embulk run -b bundle config.yml.liquid


## 
<https://qiita.com/sonots/items/979c8b0810ccffc47317>

embulk mkbundle すると、Gemfile やプラグインの雛形(gem にせずに読み込みたいプラグイン)が作られる


## memo

- Liquid の読み込まれる側ファイル名は、"_"で始まり、".yml.liquid"で終わる必要がある？
