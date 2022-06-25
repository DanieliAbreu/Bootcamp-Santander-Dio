# Anotações da Aula de Git / GitHub :book:

Link para download do Git: https://git-scm.com/downloads

#### Comando Básicos para navegação no terminal: 

##### Navegação no Windows →

- `dir`:  Da uma lista de diretórios contidos na pasta que você está
- `cd`: possibilita que navegue entre as pastas (utilizando o / → leva para a base do diretório C: )
    - Para entrar na pasta utilizar cd e a pasta que quer (ex: Windows)
    - Para voltar: **`cd ..`**
- `clear`: limpa o terminal
- tecla tab: ele auto completa a palavra
- `mkdir + nome da pasta`: cria uma pasta
- `echo`: Printa no terminal um texto, adicionando  (redirecionador de fluxo) → **>**   o output e será adicionado a um arquivo. ex: (echo hello > hello.txt)
- `del`: deleta arquivos
- seta para cima: pega todo o histórico que você já fez
- `rmdir ‘nome da pasta’ /S /Q`: remove o diretório com todas as pastas sem pedir confirmação

##### Navegação no Linux →

- `ls`:  Da uma lista de diretórios contidos na pasta que você está
- `cd`: possibilita que navegue entre as pastas (utilizando o / → leva para a base do diretório base do Linux )
    - Para entrar na parta utilizar cd e a parta que quer (ex: etc)
    - Para voltar: `cd ..`
- `clear` ou "`ctrl + l`": limpa o terminal
- `mkdir + nome da pasta`: cria uma pasta
- `echo`: Printa no terminal um texto, adicionando  (redirecionador de fluxo) → **>**   o output e será adicionado a um arquivo. ex: (echo hello > hello.txt)
- `rm -rf ‘nome da pasta’`: remove o diretório com todas as pastas internas sem pedir confirmação

#### PASSO A PASSO DO CICLO DE VIDA 

Untracked: Aquivos que o git ainda não tem ciência deles.

Tracked: Arquivos que o git tem ciência deles.

- Unmodified: Arquivo que ainda não foi modificado.
- Modified: Arquivo unmodified que sofreu alteração.
- Staged: Onde fica os arquivos que estão se preparando para fazer parte de outro tipo de agrupamento.

#### CRIANDO UM COMMIT 

- `git init`: Possibilita que o git começe de fato a gerenciar e versionar o código.

- `ls -a`: Apresenta os arquivos ocultos dentro da pasta. 
- Configurações iniciais quando for a primeira vez na máquina:
  - `git config --global user.email` `"seu e-mail"`
  - `git config --global user.name seu nome`

- `git status`: Diz em que status está o arquivo.

- `mv`: Mover arquivos para outros repositórios.

- `git add 'nome do arquivo'`: Adiciona arquivos ao staged os tornando prontos para commit

- `git commit -m "Adicionar texto ao commit"`: Para realizar o commit
- `git add*`: Pega tudo que está na working directory e adiciona para o staged.
- `git push`: Levará o repositório local para repositório remoto (poderá solicitar credenciais)