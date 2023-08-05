Olá, esta é uma mensagem criada no Readme. Pretendo usar o Git, o NeoVim e o terminal do Linux para aprender!

Este arquivo irá servir como anotações para me ajudar a lembrar dos comandos e/ou informações importantes.

*OBS: " => " serve para significado
      " -> " serve para dar um exemplo 
      " # " serve para inserir uma observação ou um comentário dentro do exemplo

Comandos do Git:
    
    git init => inicia o git

    git add => preparação para dar commit
        -> git add Readme.md
        # escreva " git status " para ter noção de quais arquivos estão prontos para dar commit

    git status => mostra quais arquivos estão prontos para dar commit

    git commit -m "mensagem" => serve para dar commit de um ou mais arquivos usando uma mensagem e enviando-os para o                                 repositório local

    git branch -M "nome da branch" => serve para mudar a branch que estará sendo utilizada
        -> git branch -M "main"
        # isso irá mudar o branch padrão "master" para "main"

    git remote add origin "link do repositório criado no GitHub" => prepara para enviar para o GitHub

    git push -u origin main => finalmente envia para o repositório remoto (GitHub)
        # para isso o git fará você passar pela autenticação, para saber se é mesmo você

