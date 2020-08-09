## Sobrescrever (reset hard)

Tem momentos que podemos fazer algo errado (não fiquei com medo, isso pode acontecer), para resolver isso você pode sobrescrever as alterações locais usando o commando

```
$ git checkout -- <arquivo>
```

Esse comando vai substitui as alterações na sua árvore de trabalho com o conteúdo mais recente no HEAD. Alterações já adicionadas ao index, bem como novos arquivos serão mantidos.

Se ao invés disso você deseja remover todas as alterações e commits locais, recupere o histórico mais recente do repositório servidor e aponte para seu branch master local desta forma.

```
$ git fetch origin
$ git reset --hard origin/master
```