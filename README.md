# iOS_studies

## GIT

Iniciar um Repositório

1. git init = cria o file inicial na pasta
2. git a . = adiciona os arquivos na Staging Area (caso eu já tenha adicionado e queira demover da Staging Area:
	git rm - -cached -r .
3. git status = ver o que está na Staging Area (add .)
5. git commit -m “texto” = adiciona os arquivos ao Local Repository
6. git log = ver o que está no Local Repository (git commit)
7. git remote add origin nomeDoLinkGeradoNoGitHub
8. git push -u origin master = adiciona os arquivos ao Remote Repository

Fluxo Git
[Working Directory] —> git add . —> [Staging Area] —> git commit -m —> [Local Repository (.git) ] —> [Remote Repository (GitHub) ]

Git Ignore/Criar arquivos
1. cd = direciona a uma pasta
2. mkdir “nome da pasta” = cria uma pasta
3. touch “nome do arquivo” = cria um file
4. touch .gitignore = cria arquivo gitignore
5. open .gitignore
6. Adicionar os itens que não quero adicionar (ex. .DS_Store)

Branch and Merging
1. git branch secondBranch = criar um nome de um branch
2. git branch = ver quais branch existem e em qual estou
3. git checkout secondBranch = entrar no secondBranch

Adicionar as alterações do secondBranch no main:
1. git checkout main (entrar no main)
2. git merge secondBranch
3. git push


Mais comandos
1. ls = listar os arquivos
2. ls -a = listar todos os arquivos (incluindo os ocultos)
3. git commit - -ammend = reescrever o commit (antes do git push)
    1. digitar i
    2. reescrever o commit
    3. digitar Esc e depois :wq
    4. git log = ver o status de alteração do commit
   

## Stacks and Heaps

Heaps: pass-by-REFERENCE
Class
Closures

SIGNIFICA:
- Quando você instancia uma CLASSE, você cria uma referência.
- Ou seja, os dados são passados por Referência.
As alterações que eu fizer no Objeto interfere nas instâncias.

Stacks: pass-by-VALUE
Structs
Enums

SIGNIFICA:
- Quando você instancia uma STRUCT, você cria uma cópia.
- Ou seja, os dados são passados por Valor.
As alterações que eu fizer na STRUCT não interfere nas instâncias.

Initializers
- STRUCTS: Já vem com initializers grátis (não é necessário escrever a func init()) 
- CLASSES: Preciso escrever init()
