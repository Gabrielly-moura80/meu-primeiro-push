# Git e GitHub

## 08/06/2026
Mesmo após instalar o git e outras ferramentas de terminal corretamente é posssivel que seu fncionamento não seja reconhecido  pelo terminal do Windows. A maioria das vezes é apenas a falta do caminho do programa na variável PATH.
Para resolver esse problema, primeiro localizamos a pasta/diretório de instalaçâo do programa, onde devemos localizar a pasta bin e copiar seu caminho.(EX.: C:git/bin). Após obter o cminho devemos abrir o Editor de Variáveis de ambiente do Windows, selecionar a PATH, clicar em EDITAR e então clicar em NOVO, para enfiar colarmos o caminho do programa.
Não podemos esquecer de reiniciar o terminal para que as alterações tomem efeito. 

## 09/06/2026
Para iniciar o git em uma pasta devemos abrir um terminal nela e digitar o comando de inicialização do Git:
git init 

Assim que o git for inicializado precisamos indicar os arquivos que devem ser rastreados. Para isso utilizamos o comando:
git add nomeDoArquivo.js

Quando os arquivos qie foram acionados para área de preparação são modificados, você verá algumas indicações no VSCode em forma de letras ao lado do nome do arquivo e alguns indicadores de cor ao lado de linhas alteradas; 