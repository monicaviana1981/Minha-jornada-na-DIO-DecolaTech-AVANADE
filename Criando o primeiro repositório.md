# Curso Git e GitHub:cat: 

## Controle de versão

#### Comando básicos para um bom desempenho:

**Windows** 

 _dir_  lista as pastas dentro de uma diretório

_cd/_ leva para a base do diretório _C:_

**Entrar na pasta do windows**

_cd dir_  vai listar todos os programas dentro da pasta do windows

**Para retroceder** 

_cd .._ utilize este comando para retroceder um nível

**Limpar a a tela do terminal**

_CTRL + L_ utilize este comando para limpar o terminal

**Teclas de Atalho**

_TAB_ função de auto completar

_CTRL + L_ limpa a tela do terminal



### Criando uma pasta no Windows

Use o comando **mkdir** + o nome da pasta, depois roda o _dir_ novamente para listar os diretórios contidos nela.

### Criando um arquivo dentro da pasta

Digite _echo_ + _>_ + o nome da pasta. Se houver alguma pasta com o nome que foi dado no comando o sistema vai retornar, caso contrário, basta dar o comando _dir_ que a pasta será criada.

### Deletando a pasta no Windows

Digite o comando _rmdir_ + o nome da pasta +  _/s/q_ 

Digite  _del_ + o nome da pasta para deletar apenas os arquivos



## Tópicos fundamentais para entender o funcionamento do Git

**SHA1** (_Secure Hash Algorithm_) conjunto de funções _hash_ criptográficas projetadas pela _NSA (Agência de Segurança Nacional dos EUA)_. Geram um conjunto de caracteres de 40 dígitos único. 

**Blobs**  bloco básico de composição.

**Trees** (_árvores_) armazenagem blobs , \0 + nome do arquivo + _sha1_ criptado com metadados 



## Ciclo de Vida dos Arquivos 

### Git Init

Quando usamos o comando _Git Init_  cria-se um repositório.

### Arquivos _Tracked e Untracked_ 

**Tracked** são arquivos em que o Git tem ciência da existência deles. Abaixo deles existem os arquivos **Unmodified**  _(arquivos ainda não modificados)_, **Modified** _(arquivos modificados)_ e **Sataged** _(arquivos que estão em processo de modificação)_ .



**Untracked**  são arquivos em que o Git ainda não tem ciência da existência deles.

## O que os repositórios significam?



Na nossa máquina, existe a separação de dois ambientes que são :

​               

​                             **Servidor**  e **Ambiente de desenvolvimento**.

####                                              Servidor

#####                                                Repositório Remoto



​                                                                                      



####                                                    Ambiente de Desenvolvimento

##### Repositório de Trabalho        Área de Staging               Local do Repositório



Como o _Git_  é o sistema distribuído, ele terá a versão dele no servido que neste caso será o _GitHub_ e também a versão que está na sua máquina. as alterações que você faz na sua máquina, ela não repercute imediatamente na versão que está em seu repositório remoto. Usando alguns comando que veremos a seguir, você empurra a alteração do   seu repositório local para o remoto.





### Conjunto de comandos

**Git status** monitora os status dos arquivos 

**Git clone** pega o clone de um repositório 



**Enviando a pasta para o controle de versão**

_git add ._  e em seguida dá o comando _git status_ . esses comandos adiciona no controle de versão local. 

Para enviar para o GitHub siga o comando abaixo:

_git commit -m " inclusão das anotações que vc fez "_ 











Link Git download  https://git-scm.com/downloads





































