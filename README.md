# (em processo de desenvolvimento >> por favor reporte os erros no issues)

<img src="https://cdn.discordapp.com/attachments/819226289789075497/1029415491858604063/git_and_github_logo.png" width="273" height="75" /> <img src="https://cdn.discordapp.com/attachments/819226289789075497/1029415491858604063/git_and_github_logo.png" width="273" height="75" /> <img src="https://cdn.discordapp.com/attachments/819226289789075497/1029415491858604063/git_and_github_logo.png" width="273" height="75" />

# Criar Chave ssh: Chave Publica:
```
    ssh-keygen -t ed25519 -c <SeuGmailDoGithub@gmail.com> 

    //a chave vai ser o 'arquivo.pub' 
    //chaveexemplo: feuawucnuaenvee5g58455g45gmail@gmail.com
```

# Inicializar ssh:
```
    eval $(ssh-agent -s)
```
# Adicionar Chave Privada:
```
    ssh-add <caminhoDaChavePRIVADA>            //colocar o caminho do diretorio da pasta
```
# Comandos Basicos:
```
    git add .                                  //adiciona todos os arquivos
        or
    git add <nomeDoArquivo>                    //adiciona arquivos especificos
    git commit -m <"nomeDoCommit">             //commitar
    git status                                 //ver status
    git push origin main                       //enviar commit para branch 'main' no GitHub
    git pull                                   //puxar arquivos do GitHub para sua maquina
```
# Clonar Repositorios:
```
    git clone <git@github.LinkDoRepositorio.git>
```
# Git Branch:
```
    git checkout -b <nomeDaBranch>               //cria uma branch
    git checkout <nomeDaBranch>                  //navega para a branch 'nomeDaBranch'
    git branch -d <nomeDaBranch>                 //deletar branch 'nomeDaBranch'
    git branch -m <nomeAtual> <novoNome>         //mudar nome da branch
                 or
    git branch -m <novoNome>                     //mudar o nome quando vc esta na branch
    git merge <nomeDaBranch>                     //juntar as branches  
    git branch -M "main"                         //mudar branch para main
```
# Git Stash:
```
    git stash save <"nomeDoStash">               //guardar conteudo de forma temporaria
    git stash list                               //ver a lista do stash, guardado em vetores
    git stash pop <indiceDoVetor>                //pegar conteúdo do stash de volta
    git stash clear                              //limpar stash
```
# Git Log:
```
    git log                                      //ver historico de commits
    git log --oneline                            //historico em uma linha 
    git log --graph                              //historico em formato de grafico    
```
# Git Reset:
```
    git reset <HEART~1>                          //voltar para ultimo commit HEART~2 HEART~3 
    git reset <id do commit>                     //passar o id do commit como parametro
```
# Git Revert:
```
    git revert <cha1>                            //voltar para o commit 
```
