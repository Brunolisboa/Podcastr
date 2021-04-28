## Podcast
Iniciado através das aulas do <next_level_week5/> organizado pela rocketseat 

## Objetivo
Desenvolver e praticar os meus conhecimentos adquiridos até o momento e evoluir a cada nova jornada de estudos e experiências Profissionais.

## Getting started
criado a partir do comando "npx create-next-app" pois o next traz uma gama de Beneficios e melhorias em relação ao "create-raect-app" React.js

1. Para executar o projeto, será necessário instalar o seguintes programas e Gerenciadores de Pacotes:
* Visual Studio Code (VScode) - (IDE - JavaScript)

2. Escolha o Método de instalação e execute como admin:
* PowerShell
* CMD

3. instalar o chocolatey e Yarn e Node.Js:
* Com o PowerShell, você deve garantir que Get-ExecutionPolicy não seja restrito. Surgiro usar Bypasspara ignorar a política para instalar as coisas ou AllSigned para um           pouco mais de segurança.
* Execute o seguinte comando: Get-ExecutionPolicy
* Se retornar "Restricted", execute Set-ExecutionPolicy AllSignedou Set-ExecutionPolicy Bypass -Scope Process
* Agora execute o seguinte comando: "Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol =                             [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))"
* Aguarde alguns segundos para que o comando seja concluído.
* Se você não encontrar nenhum erro, está pronto para usar o Chocolatey!
* Execute o seguinte comando para ver se a versão do Chocolatey está instalada em sua máquina: choco -v
* Para instalar o Yarn (Instalar), execute o seguinte comando na linha de comando ou no PowerShell: "choco install yarn"
* Execute o seguinte comando para ver se a versão do yarn está instalada em sua máquina: yarn -v
* Para instalar o Node JS (Instalar), execute o seguinte comando na linha de comando ou no PowerShell: "choco install nodejs.install"
* Execute o seguinte comando para ver se a versão do Node está instalada em sua máquina: node -v
  
4. Depois de tudo instalado executar o seguinte comando no PowerShell ou CMD, ele irá abrir o Visual Studio Code: "code ."
* Ir em Source Code Control: 4º Icone que fica no painel lateral Esquerdo do Visual Studio code
* clicar em clonar repositorio e adicionar o Link "https://github.com/Brunolisboa/Podcastr.git" e dar um Enter

5. Abrir o terminal com as teclas: Ctrl + " 
* executar os seguintes comandos para inicializar o server mockado: "yarn server", caso de erro na inicialização do servidor executar o seguinte comando "yarn add jason-           server -D" e depois o "yarn server".
* depois de executado e server abrir outro terminal e digitar: "yarn dev".
  
6. abrir o navegador 
* digitar na barra de pesquisa a seguinte url: "http://localhost:3000/"
* Pronto! Projeto inicializado.
  
## Tecnologias utilizadas no Projeto 
![](/imgs_git/stacks.jpg)

## Página Home. 
![](/imgs_git/PodcastrHome.jpg)

## Página do Episódio.
![](/imgs_git/PodcastrEpisode.jpg)

## Projeto em constante evolução!

