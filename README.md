# git

* sistema de controle de versão
* o que versiona
	* codigo fonte
	* documentação
	* manual do usuario
## comandos
* git config --global user.name
> configura seu username, usar o mesmo do git.
* git config --global user.email
> configura e-mail, usar o mesmo do git.
> os dois comandos acima sao usados para identificar você quando for colaborar em algum repositorio.
* git init
> inicia repositorio
* git status
> checa as modificaçoes
* git add
> começa a trackear um arquivo
* git commit
	* --amend edita o commit
	* -m 'mensagem' atalho para enviar commit ja com mensagem
> commita os arquivos já trakeados e prepara para enviá-los para um repositorio remoto
	
* git log
> log de commits, contem informações sobre todos os commits
* git brench (opcional("nome de nova brench"))
	* -d "nome da brench que quer deletar"
> lista as branchs e cria caso contenha o nome de uma nova brench. utilizando o parametro -d vc pode deletar uma brench, desde que não esteja nela
* git checkout
> Muda brench. Utilizando o parametro -b "nome nova brench", cria nova brench e muda para ela.

* git merge "nome da brench que voce quer mergir"
	* --continue
> Como a intenção de criar novas brenches é fazer modificações para depois enviá-las a brench principal o git merge é o comando utlizado para enviar tudo que foi feito em uma brench para outra. Para isso você precisa estar na brench que vai receber as modificações. Depois de um git merge parar de dar conflitos voce usa o git merge --continue para concluir o processo
	
* git push origin master
> envia os novos comits da master local para a master do rep remoto
* git pull origin master 
> faz download dos novos comits da master remota para a master local
* git remote prune origin
> faz update de todas as branchs locais
* flow de pullrequest
> fork -> clone -> nova branch com nova feature -> commit -> merge pra master -> commit -> Pull request

### Vitor Magno
<!-- modificações a partir daqui -->
<!-- adicione seu nome iniciando com ### assim como no exemplo acima -->

