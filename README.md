Aprendendo o GIT

Remover git da pasta = rm -rf .git
Sempre fazer "git pull" antes de qual quer coisa: git pull (Nome do repositorio) (nome da branch que deseja trazer para o local)

Iniciar o git na pasta: git init
Adicionar arquivos ao git para fazer commit depois: git add (nome do arquivo, se colocar '.' pega tudo)
Fazer um commit: git commit -m "(Mensagem para identificar oque foi feito nesse commit)"
Dizer para qual branch vai o arquivo: git branch -M (indica a branch) (Nesse caso esta criando e forçando o nome)
Dizer o local para colocar na web: git remote add (Nome do repositorio remoto) (link do repositorio).git
Colocar no repositorio: git push -u (Nome do repositorio remoto definido anteriormente) (Nome da branch a qual deseja enviar os commits) (Se nao funcionar coloca --force)
