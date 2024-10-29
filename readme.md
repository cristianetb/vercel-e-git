Bem vindo ao repo de Git/Versel

Comandos úteis:

git init: Cria um repositorio local do git na pasta.

git add .  (adiciona/prepara todos os arquivos da pasta para serem "commitados" - salvos - no repo)
git add nome_do_arquivo (adiciona um arquivo específico pra esse estado de "preparo") 


git commit -m  "requer mensagem de commit depois entre aspas" ("Comita" - "Assina" o arquivo que estamos preparando para enviar para o repositório remoto.


Mas pra assinr é necessário estar cadastrado:
git config --global user.email "seuemail@email.com"

git config --global user.name "usuariodogithub"


git remote add origin  https://endereçodoseurepo.git
git remote add meurepo2 endereçorepo2;


Como remover alguém do registro do git no Windows
Abrir o Gerenciador de Credenciais
Procurar pela credencial da vitima (o registro vai estar algo como git:https...)

Para linkar o repostiório local com o remoto e enviar as alterações "commitadas"
git push --set-upstream origin master
Só precia ser feito uma vez..

Depois disso git push basta