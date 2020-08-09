## Ramificando (Checkout)

Branches ("ramos") são utilizados para desenvolver funcionalidades isoladas umas das outras. 
Temos como padrão a branch *master* quando você cria um repositório. Use outros branches para desenvolver e mescle-os (merge que logo veremos) ao branch master após a conclusão.

![Fluxo dos ramos](../images/comandos/branches.png)

### Criando uma nova branch
Então vamos criar uma nova branch chamado *"funcionalidade_nova"* e selecione-o usando. O padrão da criação vai poder depender do projeto que vocês está trabalhando

```
$ git checkout -b funcionalidade_nova
```

### Se movendo entre branch

Você pode se movimentar entre as branch existentes no projeto, se nada na branch atual estiver pendente.

```
$ git checkout <nome da branch>
```


### Remova o branch

Se por algum motivo você não for mais utilizar a branch criada, você pode fazer a remoção dela:

```
$ git branch -d <nome da branch>
```


## Não estou visualizando minha branch no repositório
Sua branch só ficará disponível no seu repositório se for feito o processo de push.

```
$ git push origin <nome da branch>
```
