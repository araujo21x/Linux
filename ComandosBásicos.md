*cd = Mover entre as pastas;
  Ex: cd ~/Documentos/GitHub/ -> Ira para a pasta GitHub
  
*ls = Ver os arquivos da pasta atual ou de uma determinada pasta;
  Ex: ls ~/Documentos/ -> Ira mostrar todos os arquivos dessa pasta

*mkdir = Criar pasta(s) no diretorio atual;
  Ex: mkdir Pasta01 -> Ela ira criar no diretorio atual, se por vc estier em cd ~/Documentos/GitHub/ ira criar nesse local;
  Ex2:mkdir Pasta01 Pasta02 Pasta03 -> Você pode criar quantas pastas quiser so precisa da um espaço e coloca o nome da 
  outra pasta no caso;
  Ex3:mkdir Pasta\ 01 -> Vai criar uma pasta só com o nome Pasta 01, \ serve para colocar espaço;
  
*mv = Mover ou renomear o arquivo
  Ex:mv 'nome do arquivo ou pasta' 'novo nome' (no caso já estou na pasta do arquivo)-> para renomear;
  Ex2:mv 'nome do arquvo ou pasta' ~/Documentos/GitHub/ -> mover  arquivo para a pasta;

*rm -r = apaga um diretorio especifico
  Ex: rm -r 'diretorio' ~/Documentos/GitHub/" ira apagar esse diretorio;
  
*pwd = Mostrar o caminho até a pasta atual;
  Ex: pwd -> se eu estiver na pasta GitHub ira mostrar "/home/lucas/Documentos/GitHub";
  
*touch = Cria arquivos, 'nome.tipo do arquivo'
  Ex: texto.txt -> no caso criei um arquivo txt;
  
 *Extrair arquivo zip = unzip nomedoarquivo.zip;
 
 *Extrair arquivo rar = unrar x nomedoarquivo.rar;
  
*Date = Ver data;

*history = mostrar o historico dos comandos já utilizados, se coloca history 'valor' ira so mostrar
os ultimos comandos de acordo com o valor informado;

*Abrir Programa = Só precisa colocar o nome do programa;
  Ex: chromium -> ira abri o chromium. OBS = mas o terminal atual ficara tipo bloqueado, para nao acontecer 
  é só colocar '&', 'chromium &', quando voltar no terminal ao aperta a tecla 'enter' ele vai voltar ao normal.

*Para abrir arquivos = colocar o nome do programa que ler o tipo de arquivo e o nome do arquivo;
  Ex: leafpad texto.txt ou nano texto.txt -> já no diretorio do arquivo, leafpad é um editor de texto igual bloco de notas.

*Para abrir programas = sudo pacman -S 'nome do programa';
  sudo para entra no modo root, pacman -S para instalar.
  
                                                        Manjaro
                                                        
*Para instalar um programa = sudo pacman -S "nome do programa";
  Ex: sudo pacman -S chromium.
*Para instalar um programa do repositorio AUR = yaourt -S "nome do programa";
  Ex: yaourt -S chromium.
*Para procurar atualizações = sudo pacman -Su;
*Para procurar atualizações do repositorio AUR = yaourt -Syyuua;
*Para apagar programa = sudo pacman -Rsnc <nome do pacote>;
*Para fechar um programa = kill all <nome do programa/numero>;
*Para pegar o numero do programa, primeiro valor numerico que aparece com 4 digitos = ps aux | grep <nome do programa>.
