# meu repositorio de treino do git

## O que é o GIT?
É um sistema de controle de versão de codigo.

### Comandos no GIT
* __git clone__ : Clona um repositorio do servidor para a maquina do usuario.
* __git add__ : Adiciona a alteração ao arquivo.
* __git diff__ : Mostra o que foi alterado no arquivo desde o último commit desse arquivo.
* __git push__ : Coloca o commit no servidor.
* __git log__ : Mostra o historico do arquivo.
* __git status__ : Mostra o estado atual do arquivo ou repositorio.
* __git commit nome-do-arquivo.extenção -m "comentario"__ : Comita o arquivo com uma mensagem de alteração  

Quando for fazer um commit pela primeira vez:  
__git clone *nomeDoRepositorio.txt*__  
__git add *nomeDoArguivo.txt*__ (-A adiciona todos os arquivos de uma unica vez)  
__git commit -m *"texto do commit"*__  
__git push origin master__  
Para as demais vezes que for commitar o arquivo ou o conjunto de arquivos não será nescessário o comando __git clone__  

### Comandos para o terminal
* __ls__ : lista todos os arquivos dentro da pasta atual
* __rm *nomeDoArguivo.txt*__ : apaga o arquivo especificado
* __mkdir *nomeDaPasta*__ : cria uma pasta
* __cd *nomeDaPasta*__ : navega dentro da pasta especificada
* __clear__ : limpa o buffer do terminal
* __more *nomeDoArguivo.txt*__ : le o arquivo no terminal.Todo conteúdo do arquivo será exibido no terminal, preenchendo a tela com texto. Para prosseguir com a leitura, pressione a __barra de espaço__ e, caso precise voltar uma ou mais páginas, use a tecla __b__. Se quiser sair antes do fim do arquivo, pressione __q__.
* __mv__ : move arquivos e pastas ou renomeia arquivos. Se quiser enviar o arquivo de uma pasta para outra use __mv *pasta1/arquivo1.txt pasta2/*__. Se preferir apenas renomeá-lo, use __mv *arquivo1.txt arquivo2.txt*__.
* __cp__ : copia arquivos e pastas.Use o comando __cp__ seguindo do arquivo de origem e o destino. Exemplo: __cp *arquivo1.txt arquivo2.txt*__ ou, __cp *arquivo1.txt pastanova/*__. Para copiar um diretório todo, usa-se o parametro __-r__. Se quiser clonar uma pasta, usa-se __cp -r *pasta1 pasta2*__.
*O comando man deveria estar no topo de toda lista de comandos importantes do Linux. A razão é muito simples: basta executá-lo para carregar uma página de manual (man page) sobre os comandos do sistema, com definições não apenas do uso de cada ferramenta, mas também descrições detalhadas dos inúmeros parâmetros do software e exemplos de uso.
