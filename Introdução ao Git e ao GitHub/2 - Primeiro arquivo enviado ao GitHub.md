Para o primeiro envio de informações para o GitHub, é necessário que tenha algum arquivo no diretório local.
Executar o Git no diretório ou direcionar o caminho do Git até o diretório em que tenham as informações à serem transportadas.

Listar os arquivos no diretório, utilizando o comando *ls*

Verificar se há itens não comitados, utilizando o comando *git status*
Caso algum item fique vermelho, significa que não foi adicionado nenhum item a ser comitado.

Adicionar o arquivo modificado ao controle de versionamento: *git add . *

Verificar o status novamente: *git status*
Caso tenham itens na cor verde, significam que foram adicionados para realizar o commit. 

Realizar o commit dos arquivos: *git commit -m "<anotações>"*


Após realizar o commit, podemos enviar as informações para o GitHub, utilizando o comando *git push origin main*