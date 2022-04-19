#Comandos

CTRL L - limpa

ls - lista todos os arquivos no local em que você está.

cd - cd + pasta faz com que você entre na pasta desejada

mkdir - (make a dir) cria uma pasta (colocar nome da pasta na frente)

ls -a - mostra arquivos ocultos (flag -a)
git status - traz informações sobre a situação (diretório, pasta, etc)

mv - cd .. - volta para pasta anterior

git commit -m “nome que vai dar” - Comita o arquivo/pasta em questão, gerando um sha1 (40 caracteres)

git add* - adiciona tudo da area de trabalho que foi alterado para o stage, para commitar.



--------------------------

# Criando Repositório 

- Criar um novo repositório no github, 
- selecionar a opção “add a readmefile” para facilitar.
- Copiar o https do github
- Abrir o “git Bash HEre” na pasta que deseja
- Usar o comando **Git clone “URL”** que copiou no github
- Para enviar essa pasta da maquina para o github, primeiro tenho que usar o comando **git add .** para adicionar todas as alterações que fiz e salvar na maquina.
- git commit -m "mensagem que eu quero que apareça lá"
- Por fim, dar o comando git push origin main