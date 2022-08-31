# GIT FLOW

Projeto feito enquanto eu aprendia a utilizar os comandos do Git Flow.

<hr>

## Comando para configurar ambiente git flow
git flow init -> Configura o GIT FLOW

 ## Criando novas Features
git flow feature start <NOME_FEATURE> -> Cria uma nova feature

git flow feature finish <NOME_FEATURE> -> Faz merge da feature na branch de desenvolvimento

## Criando novas Releases

git flow release start <VERSAO_PROJETO>

git flow release finish <VERSAO_PROJETO>

<b>Obs:</b> Em casos de pequenas alterações ou BUGS simples, estes podem ser resolvidos dentro na própria release branch.
## Finalizando
Subir as atualizações
git push origin --all


## Publicar branch para outros DEVS
git flow feature publish <NOME_FEATURE>