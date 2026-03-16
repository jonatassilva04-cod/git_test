gitpara um repositorio remoto

##Comandos Git

git init "inicia um repositorio"

git config " para configurar seu repositorio"

git branch -M main \\ Define Main como Repositorio Princioal
git config --global usser \\configuração  geral do projeto
git config --global user.name \\ nomear usuario do projeto
git config --global user.email \\ nomear email do projeto


git remote add origin https://github.com/<conta_do_usuario>/<nome_do_repositorio>
(conecta com o repositorio remoto)

git status   -- Verificar status do projeto
git add      --git add adiciona arquivos para a área de preparação (staging area)
git add .    --adiciona todos os arquivos
git commit ""-- para o dev documentas informando o andamento do projeto
git push     -- envia os commits do repositório local para o repositório remoto
git pull     -- baixa e atualiza o repositório local com as alterações do remoto
#Primeiros comandos
Ao estruturar suas pastas e arquivos, crie na pastaROOT ou pasta principal do projeto
e crie 2 arquivos Importantes do git

.gitignore --(quais arquivos o Git deve ignorar.)

README.md --(Responsavel por Informar o escopo do projeto des da sua arquiteturas, ambientes e o proposito do projeto e o nome do autor e sua equipe ).

