# CMD
>*obs: apertar a tecla "TAB" ele autocompleta o caminho de pasta no comando cd*
>
>*obs: apertar a tecla "setinha pra cima" fará com que o comando anterior utilizado reaparessa*

+ `dir` ⏩ mostrará todas as pastas do diretório atual que vc pode entrar
+ `cd (caminho)` ⏩ irá entrar no endereço de diretório escrito
>*obs: cd .. ⏩ retrocede uma página*
+ `cls` ⏩ limpa a tela do cmd
+ `mkdir (nome_da_pasta)` ⏩ cria pasta dentro do diretório atual
+ `echo (String)` ⏩ printa na tela a frase que vc digitar
+ `echo (String)` > (nomedoarquivo.txt) ⏩ cria um arquivo txt com a String selecionada
+ `del (nomedapasta)` ⏩ deleta todos os arquivos da pasta
+ `rmdir (nomedapasta) /S /Q` ⏩ deleta a pasta e os arquivos
+ `cd /d D:\Tuca 2` ⏩ mudando o diretório base de busca

***
# Git
>*obs: CTRL + L ⏩ limpa tela*

+ `openssl sha1 (nomedoarquivo.extensão)` ⏩ mostra o arquivo criptografado em SHA1
+ `ssh-keygen -t ed25519 -C guga_camil@hotmail.com` ⏩ gera chave SSH de segurança
+ `ls` ⏩ lista os arquivos da pasta atual
+ `cat (nomedoarquivo.extensão)` ⏩ mostra o conteúdo do arquivo desejado
+ `pwd` ⏩ mostra o diretório em que estás
+ `eval $(ssh-agent -s)` ⏩ cria um agente gerenciador de ssh's
+ `ssh-add (caminho da chave SSH)` ⏩ coloca qual a chave para o gerenciador gerenciar
+ `mv nomedoarquivo.extensão (diretório para o qual será movido)` ⏩ move o arquivo para alguma pasta

+ `git init` ⏩ cria repositório git dentro da pasta atual
+ `git clone (URL do repositório)` ⏩ clona o repositório desejado para os seus arquivos
+ `git config --list` ⏩ mostra os dados do programador. OBS: apertar Q para sair da lista
+ `git config user.email "email"` ⏩ configura o email padrão do usuário. OBS:  se colocar a tag --unset, ele retirará o email/name cadastrado
+ `git config user.name (Nome)` ⏩ configura o nome padrão do usuário obs: se colocar a flag --global dps de config, será para todos os repositórios
+ `git add (o que irá ser empacotado)` ⏩ empacota oq será comittado. Se quiser empacotar todos os arquivos colocar *
+ `git commit -m "Informação do commit"` ⏩ committa o que estava empacotado
+ `git status` ⏩ fala se precisa committar ou stagiar algo
+ `git restore --staged (nome do arquivo/pasta)` ⏩ para tirar do STAGING AREA
+ `git remote add origin (URL)` ⏩ adiciona a "nuvem" github ao qual o projeto atual irá ser pushado
>*obs: origin é o apelido desse repositório online*
+ `git push origin master` ⏩ pusha para o origin na branch master
+ `git pull origin master` ⏩ atualiza o repositório local de acordo com o repositório remoto

***
# FLAGS

+ -a ⏩ mostra pastas ocultas. Ex: ls -a -> mostra as pastas ocultas dentro do diretório atual
+ --global ⏩ configuração será para todos os repositórios
+ --unset ⏩ reinicia para null
