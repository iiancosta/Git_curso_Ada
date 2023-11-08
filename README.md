# git_curso_ada
Nesse documento apresento meus aprendizados para utilização do Git.

## git status
Vemos qual é a situação que os arquivos estão, se houve alguma modificação e se algo precisa ser salvo ou descartado.

## git diff
Mostra as modificações no arquivo após um add.

* git diff --staged
Mostra todas as modificações do arquivo após o commit.

## git add
Usado para adicionar o que será comitado.
* 'use "git add <file>..." to update what will be committed'

## git log
Apresenta o histórico de commits feitos.
* Use 'git log --oneline --decorate' para veirificar o branch principal

## git restore
Dá um crtl+z no arquivo.

* git restore --staged <file>
Retira o arquivo do staged (remove o add) e vai para área de modificado.

## git push
Envia os commits para o repisitório remoto.

## git pull
Adiciona tudo que está no repositório remoto para o local.

## git fetch
Apresenta as modificações que o repositório remoto tem para serem adicionadas com o pull.
* use git diff origin/master para visualizar

## git branch
* Use "git branch" para ver as branchs que existem e a atual 
* Use "git branch 'nova-branch'" para criar uma nova branch

## git merge
Utilizado para mesclar diferentes branchs. É interessante que se observe as modificações feitas para que caso sejam feitas modificações em um único arquivo corrija-se antes que entre em algum conflito.