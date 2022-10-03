# Github - Comandos básicos (Sobrevivência)

## 1 - Inicializando um repositório
- Inicializa o versionamento no respectivo diretório
```
git init 
```
## 2 - Status e Commit
- Verifica o status do repositório
```
git status 
```
- Adiciona todos os arquivos para serem commitados
```
git add . 
```

- inserir um comentário 
```
git commit -m "my commit"
```

## 3 - Visualizando relatório de commits
- Todos os commits
```
git log 
```

- Exibe log com hash e título do commit
```
git log --oneline 
```

## 4 - Repositórios
- Adicionando um repositório remoto

```
git remote add origin https://github.com/Usuario/Repositorio.git
```

- Enviando as modificações para o repositório remoto
```
git push origin <branch>
```

- Puxando alterações do repositório remoto
```
git pull origin <branch>
```

## 5 Trabalhando com Branchs
- Criando uma nova branch e alterando para ela

```
git checkout -b nome-branch 
```

- Fazendo merge em branchs
_precisa estar na branch de destino_

```
git merge nome-branch
```
- Visualizando todas as branches existentes no repositório

```
git branch
```
- Deletando uma branch local
```
git branch -D nome-branch
```

- Deletando uma branch remoto
```
git push origin :nome-branch
```
