Comando git aprendidos:

ssh-keygen -t ed25519 -C "email da conta github" = criar chave de acesso ao github.	Cria chave de acesso ao Github

git init	Para iniciar um repositório git

git add	Adicionar arquivos área de stage, para ficarem produtos para o commit.
depois do comando coloque o nome dos arquivos que quer adicionar ou coloque um ponto se quiser adicionar todos

git commit -m “Mensagem”	Serve para registrar as alterações feitas nos arquivos

git remote add origin (url do repositório github)	Serve para fazer a conexão entre o repositório do git com o do github

git push -u origin main	Serve para emburrar os arquivos para o repositório do Gihub

git branch -m “nome”	Serve para mudar o nome da branch

git checkout -b “nova branch”	Serve para criar uma nova branch 

git checkout (nome da branch)	Serve para mudar de branch, coloque o nome da branch que deseja entrar

git merge (nome da branch)	Serve para juntar as branch, tem que ta dentro da main e no fim do comando colocar o nome da branch que vc quer juntar com o main

git clone (URL do repositorio)	Serve para clonar os arquivos de um  repositório do Github