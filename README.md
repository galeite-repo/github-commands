## 1 Inicializando um repositório

git init - "Inicializa o versionamento no respectivo diretório"

# 2 Comandos básicos para sobreviver
git status - "Verifica o status do repositório"

git add . - "Adiciona todos os arquivos para serem commitados"

git commit -m "inserir um comentário significativo"


# 3 - Visualizando relatório de commits

git log // todos os commits
git log --oneline // exibe log com hash e título do commit
Adicionando um repositório remoto

git remote add origin https://github.com/User/Repository.git
Enviando as modificações para o repositório remoto

git push origin <branch>
Puxando alterações do repositório remoto

git pull origin <branch>
4 Trabalhando com branchs
Criando e locomovendo-se para uma nova branch

git checkout -b nome-branch 
Aplicando merge em branchs

git merge nome-branch // precisa estar na branch de destino
Visualizando todas as branches existentes no repositório

git branch
Deletando uma branch local

git branch -D nome-branch
Deletando uma branch remoto

git push origin :nome-branch

