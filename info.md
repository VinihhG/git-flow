# Iniciando
git flow init -> Configura o GIT FLOW

 ## Criando novas Features
git flow feature start <NOME_FEATURE> -> Cria uma nova feature

git flow feature finish <NOME_FEATURE> -> Termina uma nova feature

## Criando releases <b>Para Testes</b>

git flow release start <VERSAO_PROJETO>

<b>Obs:</b> Se der BUG eu resolvo na própria RELEASE

git flow release finish <VERSAO_PROJETO>

## Finalizando
Subir as atualizações
git push origin --all

## No Servidor
git tag
git checkout <TAG>



## Publicar branch para outros DEVS
git flow feature publish <NOME_FEATURE>