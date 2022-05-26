#### chave css  ao commit

$ **ssh-keygen-t ed25519 -C** *e-mail* *  

local do  file

senha

senha

$ **cd /** *caminho da pasta* (ex : c/Users/client/ .ssh/ )

$ **cat id_ed25519.pub**

$**eval $(ssh-agent -s)** 

$**ssh-add id_ed25519**



#### Criando Repositório

A pasta já deve ter sido criada (/c/workspace/)

$**mkdir** *nome da pasta a ser criada* (ex: celiaco)

$**cd ** *nome da pasta criada*

(/c/workspace/nova pasta/)

$**git init**

$**git config --global user.email** *email do hub*

$**git config --global user.name** *mesmo nome da hub*

deve criar arquivo em .md (usei a Typora)

$**git add * **

$**git commit -m "commit inicial"**

$**mkdir** *nome da nova 2º pasta* (ex: conteudo)

$**mv** *nome do arquivo ./nova pasta (ex: Umbairro.md ./conteudo)

$**git add** *nome do arquivo nome da pasta* 

$**git commit -m** *" texto"*  (ex: criado conteúdo,mv para conteúdo)

$ **echo > README.md**

(aqui abrir o arquivo e escrever o que deseja, considero como uma introdução do projeto)

