# ProjetoGit
Command Line Interface (Usar o git para lincar as pasta no computador no GitHub).

0- Para limpar o GIT
$ clear

1-	Crie uma pasta;

2-	No GIT:

$ cd “local da pasta” ;
$ git clone “HTTPS do GitHub ;

3-	No VSC:
**** Alterações *****

4-	No GIT:
$ ll ;
$ cd “Pasta” ;
$ git status ;
$ git add “nome do arquivo em vermelho” ;
$git status (Vai ficar verde) ;
Se for a primeira vez acrescente :
$ git commit -m “Update nome do arquivo” ;
$ git conf –global user.email “email” ;
$ git conf –global user.name “nome” ;
$ git commit -m “Update nome da pasta” ;
$ git status ;
$ git push ;

5-	Vá no GitHub:
Perfil > Settings > Developer Settings > Personal Tokens > Generate new token > nomes da pasta + [] repo >
Geretate Token> copie o Token

6-	Volte para tela e cole e pronto.

7-	Renomear pasta;

8-	No GIT:
$ cd “local da pasta” ;
$ git clone “HTTPS do GitHub ;

9-	No VSC:
**** Alterações *****

10-	No GIT:
$ cd “Pasta” ;
$ git status ;
$ git add . (altera tudo) ;
$git status (Vai ficar verde) ;
$ git commit -m “Update nome do arquivo” ;
$ git status ;
$ git push ;

11-	Salva Todos os commit
$ cd .. (volta) ;
$ cd “outra pasta” ;
$ git status ;
$ git log ;
$ git fetch ;
$ git status ;
$ git pull ;

12- Criar e ir para nova branches
$ git checkout -b "novo" ;

13- Para mudar as branches
$ git checkout main ou outra branches ;

14- Juntar com branche main
$ git merge NOVO ;
$ git push ;

15- Puxar alteração do GitHub para pasta
$ 
git pull
