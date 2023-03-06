# Javascript-Commentary

logonrmlocal@PA403MICRO39 MINGW64 ~

$ cd desktop //entra no desktop(pasta)

$ mkdir Aulagit //cria pasta "Aulagit"

$ cd Aulagit //acessa tal pasta

$ ls //diz conteudo da pasta

$ git init //inicia github + dá master

$ git config --global user.name "Felipe" //configura conta

$ git config --global user.email felipe.arnus@gmail.com //acessa email do git

$ git status //vê pastas linkadas e não linkadas ao PROMPT
-----------------------------------------------------------------------------------------------
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed) //aula.txt não esta adicionado
        aula.txt

nothing added to commit but untracked files present (use "git add" to track)
-----------------------------------------------------------------------------------------------

$ git add . //adiciona todas não conectadas

$ git add aula.txt //adiciona "aula.txt" especificamente 

___________________________________________________________________________________________________________
NOTA 
Ao modificar o interior de algum programa (aula.txt) é necessario que a pasta seja re-adicionada ao PROMPT
___________________________________________________________________________________________________________

$ git log //mostra tudo linkado ao PROMPT + dá um endereço
----------------------------------------------------------------------------------------------------------------
commit c4836c075f92220823df8cb4e28470aafa94c67a (HEAD -> master) //a combinação de letras e numeros pós commit
Author: Felipe <felipe.arnus@gmail.com>
Date:   Mon Mar 6 11:14:44 2023 -0300
----------------------------------------------------------------------------------------------------------------

$ git show c4836c075f92220823df8cb4e28470aafa94c67a //mostra conteudo dentro do "aula.txt"


