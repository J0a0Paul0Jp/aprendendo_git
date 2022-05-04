# Aprendendo git...

Comandos mais básicos
```
git init #iniciar um novo repositório
git add file ou git add . #para adicionar arquivos ao seu repositório
git status #verifica status do commit do repositório local
git commit -m "uma coisa relacionada ao seu commit" #fazer commit
git log #mostra os logs dos commits
git push #subir seu repositório para um servidor remoto
- git push -u  https://github.com/J0a0Paul0Jp/aprendendo_git 
   #subir um branch diferente do master pela primeira vez
- git push --set-upstream origin vingadores
   #subir um branch fora do master
   
```
# Você pode também dividir seu repositório para ser mais divertido trabalhar em equipe :)
Veja abaixo mais comandos:
```
git branch #mostra em qual estado de branch está
git branch dev #nesse exemplo vai ser criado uma nova branch chamanda de 'dev'
git checkout -b #assim como no comando acima irá ser criada uma nova branch, porém já pronta pra ser trabalhada
git checkout dev #agora o estado atual da branch vai ser mudada pra dev
```

podemos também juntar uma branch a outra, muito útil quando se tem vários programadores trabalhando em branch diferentes de um mesmo sistema
veja mais abaixo

```
git checkout master
git merge dev
#nesses dois útlimos comandos, o estado do repositório local foi mudado para master e logo em seguida foi feito o merge com o dev
```

## git reset ...
```
git reset -- arquivo. #se você deseja excluir um arquivo previamente adicionado do commit, você pode voltar estado anterior
git reset --soft HEAD^ #uma forma de desfazer seu ultimo commit
```
## é isso, aprendeu?
