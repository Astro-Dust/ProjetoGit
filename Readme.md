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

    git add . => peparação de todos os arquivos para o commit

    git status => mostra quais arquivos estão prontos para dar commit

    git commit -m "mensagem" => serve para dar commit de um ou mais arquivos usando uma mensagem e enviando-os para o                                 repositório local

    git branch -M "nome da branch" => serve para mudar a branch que estará sendo utilizada
        -> git branch -M "main"
        # isso irá mudar o branch padrão "master" para "main"

    git remote add origin "link do repositório criado no GitHub" => prepara para enviar para o GitHub

    git push -u origin main => finalmente envia para o repositório remoto (GitHub)
        # para isso o git fará você passar pela autenticação, para saber se é mesmo você

    git push origin main => envia para o repositório remoto
        # normalmente, não é mais pedido para se autenticar quando der um "push". Então foi só excluir o "-u" do comando
        
    git checkout -b "nome da branch nova" => isso irá criar a nova branch chamada "novo-botao" e você estará dentro dela. Você pode criar arquivos que pertencem apenas a ela, como por exemplo o arquivo "botao.html"
     	-> git checkout -b "novo-botao"
     	# depois de criado os arquivos necessários, é só dar um " git add . " e depois "git push origin novo-botao". Atentar-se que não é main, e sim novo-botao, neste caso.

   git checkout "nome da branch"
   	-> git checkout main
   	# muda a branch para a escolhida
   	
   git merge "branch escolhida" => serve para pegar a branch criada e juntar com a principal (main)
   	-> git merge novo-botao
   	# lembrar de mudar para a branch principal:
   		1. git checkout main
   		2. git merge novo-botao
   		
   git clone "link".git => serve para clonar um repositório qualquer do GitHub (no caso é a URL.git)
   		
   git pull => serve para atualizar um arquivo que foi clonado do GitHub (precisa estar dentro da pasta do arquivo)
   	-> git pull GitTutorial
   	# é basicamente isso. Já vai atualizar automaticamente



