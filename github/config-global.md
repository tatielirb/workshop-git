## Config Global

A primeire coisa que você deve fazer ao instalar Git é nós indentificar para o Git, esse passo é importante porque cada commit usa esta informação para que todas as modificações tenham a assinatura do nosse ususer.
Execute os dois seguintes comandos com seu nome e e-mail respectivamente:

```
$ git config --global user.name "Seu nome"
$ git config --global user.email "seu-email@example.com"
```

Essa indentificação de assinatura vai ser mostrado no GitHub na lista de commits (Históricos) ou em outros pontos, como Pull Request (que vamos ver mais para frente):

![Imagem que mostra uma lista de commit com os dados do user que acriou](../images/comandos/config-global-list.png)

