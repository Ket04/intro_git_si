# Comandos principais do Git

git log - exibe as alterações feitas, os commits realizados (adicione -oneline pra exibir de forma reduzida).

git add . - junta todos os arquivos alterados para ser realizado o commit (leva eles para o stage).

git commit -m "texto" - faz um commit com um texto, normalmente escrito pelo usuário para detalhar o que foi alterado.

git restore . - volta para o ultimo commit feito.

git restore --staged . (ou nome do arquivo) - remove os arquivos enviados para o stage.

clear - limpa o terminal.

git reset --hard - independente do local ou etapa que estiver, volta para o ultimo commit realizado.

git diff (nome do arquivo) - mostra o que está de diferente do arquivo atual para o ultimo commit realizado.

git diff --staged - mostra o que está de diferente dos arquivos preparados para o stage.

git checkout (hash do commit) - navega entre os commits feitos, utilize main para voltar ao mais atual.

git branch - lista as branchs existentes

 git branch (nome) - cria uma nova branch

 git switch (nome da branch) - navega entre as branchs

 git merge (nome da branch que vc quer mesclar com a main) - junta as alterações com a branch main, antes precisa ser feito o commit dentro da branch com as alterações, retornar a main e depois rodar o merge!

 

# **CUIDADO**

git reset HEAD~1 --soft - Deleta o registro do commit feito, menos suas alterações realizadas (o que estiver dentro do staged ou esperando para ser enviado pra lá).

git reset HEAD~1 --hard - Delete o registro, o que estiver no staged e fora dele, voltando para o ultimo commit feito.