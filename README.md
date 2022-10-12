# notepad git/github   (em processo de desenvolvimento)

<img src="https://cdn.discordapp.com/attachments/819226289789075497/1029415491858604063/git_and_github_logo.png" width="820" height="200" />

# Criar Chave ssh: Chave Publica:
```
     ssh-keygen -t ed25519 -c SeuGmailDoGithub@gmail.com 
```
//a chave vai ser o 'arquivo.pub' 
//chaveexemplo:feuawucnuaenvee5g58455g45gmail@gmail.com

# Inicializar ssh:
```
    eval $(ssh-agent -s)
```
# Adicionar Chave Privada:
```
    ssh-add 'caminhoDaChavePRIVADA'
```
# Comandos Basicos:
```
    git add .   ||   git add <nomeDoArquivo>   //adiciona arquivos
    git status                                 //ve status
    git commit -m <"nomeDoCommit">             //commitar
    git push origin main                       //enviar commit para branch 'main' no GitHub
    git pull                                   //puxar arquivos do GitHub para sua maquina
```
# Clonar Repositorios:
```
    git clone <git@github.LinkDoRepositorio.git>
```
# Branch:
```
    git checkout -b <nomeDaBranch>               //cria uma branch
    git checkout <nomeDaBranch>                  //navega para a branch 'nomeDaBranch'
    git branch -d <nomeDaBranch>                 //deletar branch 'nomeDaBranch'
    git branch -m <novoNome>                     //mudar nome da branch
    git branch -m <nomeAtual> <novoNome>
                 or
    git branch -m <novoNome>                     //mudar o nome quando vc esta na branch
```
# Git Stash:
```
```


#


#
