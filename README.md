# GitHub_study

- primeiros comandos  

**cd** entra em um diret�rio  
**cd ..** sai de um diret�rio  
**clear** limpa tela do terminal  
**git init** cria um reposit�rio vazio (� criada a pasta .git, oculta no windows)  
**git status** mostra a situa��o do reposit�rio  

**git add** adiciona um arquivo stage  
**git add *.txt** adiciona todos os arquivos do mesmo tipo  
**git add .** adiciona todos os arquivos de todos os tipos  
**git commit -m "coment�rio"**confirma o envio  
**git commit -a -m "Comentario"** faz o add e o comit ao mesmo tempo, sem passar pelo stage  

**.gitignore** n�o transfere para o reposit�rio o que estiver definido neste arquivo  

# resumo
1 - adicionar arquivos local  
2 - git add, envia seus arquivos para o stage (area de espera)  
3 - commit, confirma o envio dos arquivos para o reposit�rio  

# comandos diversos
**git diff** verifica as altera��es feitas localmente  
**git log** hist�rico de todos os commits  
**q**finaliza o relat�rio de log  
**gitk** abre interface de relat�rios de altera��es  
**git log --pretty=oneline** mostra os commits sem detalhes  
**git commit --amend -m "altera o comit anterior"** edita o commit mais recente  
**git reset HEAD nome-arquivo** remove um arquivo da stage  
**git checkout --nomearquivo** descarta altera��es feitas num arquivo na stage  
**git rm arquivo** elimina um arquivo  


# tags
- servem para marcar um ponto no controle de vers�o e transitar entre estes pontos. Ex: tem a vers�o 0.0 e 1.0, criando uma tag � possivel transitar entre estas vers�es e verificar como era o projeto em cada uma delas. O melhor para criar vers�es s�o os branch.

**git tag -a v0.0 (chavedocommit) -m "Vers�o 0.0"**
**git tag** lista as tags existentes  
**git show (tag)** mostrar informa��es da tag  
**git checkout (tag)** muda para a tag espec�fica  
**git checkout master** volta para a tag master  
**git tag -d (tag)** deletar uma tag  


# branch
**git branch teste** cria um branch de teste  
**git checkout teste** muda do branch master para teste  
**git checkout -b teste** cria o branch teste e j� muda para ele  
**git merge teste** mistura as altera��es do branch teste com o branch master  
**git branch -d teste** deleta o branch teste  


# git e github online
**git push origin master** envia as altera��es do pc para o github


# comandos de formata��o do README.md
**texto em negrito** colocar o texto entre dois pares de *  
- lista com marcador (usar - )  

criar link ( [colocar o texto entre colchetes] (e o endere�o na frente entre chaves))

- teste  

# nivel 1  
## nivel 2  
### nivel 3  
#### nivel 4  

