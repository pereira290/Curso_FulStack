



Linha de comando    
    echo "# Curso_FulStack" >> README.md 
    git init 
    git status

Configurar o git no PC
  git config --global user.email "pereira-290@hotmail.com"
  git config --global user.name "pereira290"
  
associar o ficheiro README.md ao repositorio   
  adicionar arquivos ao controlo de versao
    git add README.md (ou add .)
  carregar os ficheiros   
    git commit -m "mensagem util a informar a operacao" 

  Criar e direcionar a branch de trabalho 
    git branch 
        (mostra as branchs existentes)
    git branch <nome>
        (cria nova branch "nome"
    git chekout <nome>     
        (mudar para branch "nome")
    git branch -M main 
  Identificar o local do projeto (branch - caminho - pastas, diviões, etc) no git (ver linq em CODE)  
    git remote add origin git@github.com:pereira290/Curso_FulStack.git
  Subir os ficheiros para o git (online)  
    git push -u origin main

.. Juntar codigos entre branchs 
    git checkout <nome da branche que quero atualizar>
    git marge <nome da branch onde tenho os arquivos a tranportar>
    git push
       
.. atualizar ficheiros (modificar o ficheiro no PC)
    git status
    git add .
    git commit -m "mensagem para historico"
    git push 

.. atualizar os ficheiros do PC em conformidade com o git
    git pull 

…ou envie um repositório existente a partir da linha de comando
    git remoto adicionar origem git@github.com:pereira290/Curso_FulStack.git
    git branch -M principal 
    git push -u origem principal

…ou carregar um repositorio para o pc
    git remoto adicionar origem <link existente no code>
    git pull origin main

.. converter master ou outro para main
    git status 
    git checkout -b main
    
.. historico de commits
    git log --oneline
    
.. Voltar para uma versão anterior ou outra
    git reflog
    (copiar o ID ??????? HEAD@/1=:... da versão que se pretende)
    git reset --hard ???????
    
.. ignorar ficheiros (manter apenas no PC) - cria um ficheiro para adicionar ficheiros a ignurar - utlilizar notepad
    touch .gitignore       (escrever dento - <nome arquivo>/
                                            foto.png
                                            etc)
                                            
    
