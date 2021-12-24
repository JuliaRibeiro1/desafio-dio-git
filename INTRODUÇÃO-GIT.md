---INTRODUÇÃO AO GIT---

**GUIT
  É um sistema de controle de versões distribuído, que registra as alterações feitas no código e é possível regredir a versões anteriores, se necessário. O git também facilita o compartilhamento de um projeto e o trabalho em equipe.

**GUI VS CLI
  GUI (Graphical User Interface) possui uma interface gráfica, ou seja, o usuário consegue realizar praticamente tudo sem precisar saber comandos mais complexos e o CLI(Command Line Interface) não possui uma interface gráfica, que é o caso do GIT e é preciso usar comandos. 

**Comandos GUIT
  -->git init
    inicializar o código.
  -->ls -a
    mostra as pastas ocultas.
  -->git status
    vai mostrar se o arquivo está untracked, modified, staged…
  -->git log
    vai mostrar todas as alterações feitas no branch atual, bem como as informações de quem as fez.
  -->git commit 
    para salvar alterações usar git commit -m “Nome do commit”.
  -->git branch
    serve para mostrar o branch atual.
  -->git clone
    serve para copiar todos os arquivos do repositório remoto para o repositório local. Exemplo: git clone + o o link ou SSH do repositório.
  -->dir
    mostra todos os arquivos e subpastas em uma pasta. No linux, esse comando é ls.
  -->cls
    serve para limpar o terminal, no linux usamos clear. No git é usado CTRL + L.
  -->cd
    serve para navegar por um local específico no sistema.
  -->TAB
    possui a função de autocompletar.
  -->mkdir
    serve para criar uma pasta.
  -->criando arquivo
    echo hello
    echo hello > hello.txt (o "hello" é o conteúdo do arquivo de texto hello).
  -->del
    usado para excluir os arquivos de uma pasta.
  -->rmdir
    é usado para deletar a pasta.
  -->git push origin main
    Serve para enviar arquivos do repositório local para o remoto.Primeiro é preciso que o GIT reconheça o arquivo (usar git add-A ou git add .) e depois commitar. E aí usar git push origin main.


CICLO DE VIDA DOS ARQUIVOS NO GIT

**Untracked
  se refere aos arquivos que o git não sabe que existe ainda.
**Tracked
  são os arquivos que o git conhece.
**Staged
  prepara o arquivo para o commit e permite que você confirme algumas alterações desde o último commit. E aí o ciclo começa de novo.

**Alguns termos usados no GIT
  -->Master 
    master se refere a uma versão principal do sistema.
  -->Branch
    é um tipo de ramificação do master.
  -->README
    é um texto que serve para descrever o projeto, como ele funciona ,informações importantes sobre ele e etc.










