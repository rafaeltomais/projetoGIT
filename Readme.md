Olá, neste projeto irei aprender a usar o GIT.

<!--
Primeiros passos:
sempre que for digitar um comando, precisa começar com 'git'
git --version |Para ver a versão que está instalado o GIT
git init |Criar diretório local
git add Readme.md |Cria um arquivo "Readme.md" no diretório. 'add' é para deixar na area de standing
git status |Ver se existe algo para 'commitar'
git commit -m "primeiro commit" |Commitar o arquivo com a descrição "primeiro commit"
git branch -M "main" |Mudar a branch "master" para "main"
git remote add origin https://github.com/rafaeltomais/projetoGIT.git |remote é a conexão dos dois repositorios (local e github). Add pra adicionar e 'origin' é o apelido da conexão
git push -u origin main |Empurrar o que criou em origin para a branch 'main'

Adicionar ou alterar:
git add . |Coloca todos os arquivos alterados e salvos em standing
Não precisa criar outro remote, pois a conexão é feita apenas uma vez

Crianco uma branch:
git checkout -b "novo-botao" |sai da branch 'main' e cria (e já entra na branch 'novo-botao')
git commit -m "novo-botao" 
Para ver em qual branch que está, é só olhar no bash.

Para alterar entre as branches:
git checkout main
git checkout novo-botao

Para juntar a branch onde vc estiver (geralmente a main):
git merge novo-botao

Para clonar o repositorio pra maquina local:
git clone 'url do repositorio'

Passos para subir pro Github quando alterar o código:
- altere o código do projeto
- salva na máquina local
- em BASH digitar comando 'git add .'
- em BASH digitar comando 'git commit -m "Nome do commit"'
- em BASH digitar comando 'git push origin *nome da branch sem aspas*'
 -->
