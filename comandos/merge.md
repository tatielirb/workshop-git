## Mesclar (merge)
 
 
Outro comando que usamos muito quando trabalhamos em equipe e com criação de branch para novas funcionalidade no desenvolvimento é o comando de `merge`. Para fazer merge de um outro branch ao seu branch ativo (ex. develop), você pode utilizar:
 
```
git merge <branch>
```
Nesse processo o git tenta fazer o merge das alterações automaticamente. Mas temos alguns detalhes nesse processo por algum motivo podem surgir resultados de conflitos entre, isso acontece pois as vezes o git não consegue sozinho resolver alterações que foram feitos no mesmo arquivo e em alterações em uma mesma funcionalidade. Isso não é uma falha e sim um mecanismo de segurança para que nada seja perdido nesse processo. Nesse caso o usuário ficará responsável por fazer o merge nestes conflitos manualmente editando os arquivos exibidos pelo git.
 
Depois de alterar, você precisa marcá-los como merged com
```
git add <arquivo alterado>
```
 
Antes de fazer o merge das alterações, você pode também pré-visualizá-as usando
 
```
git diff <branch origem> <branch destino>
```
 
Às vezes podem ocorrer o processo do merge e não ter conflitos.
