## Podcast
Iniciado através das aulas do <next_level_week5/> organizado pela rocketseat 

## Objetivo
Desenvolver e praticar os meus conhecimentos adquiridos até o momento e evoluir a cada nova jornada de estudos e experiências Profissionais.

## Getting started
criado a partir do comando "npx create-next-app" pois o next traz uma gama de Beneficios e melhorias em relação ao "create-raect-app" React.js

1. Para executar o projeto, será necessário instalar o seguintes programas e Gerenciadores de Pacotes:
* Visual Studio Code (VScode) - (IDE - JavaScript)

3. Escolha o Método de instalação e execute como admin:
* PowerShell
* CMD

4. instalar o chocolatey e Yarn e Node.Js:
  4.1 Com o PowerShell, você deve garantir que Get-ExecutionPolicy não seja restrito. Surgiro usar Bypasspara ignorar a política para instalar as coisas ou AllSigned para um           pouco mais de segurança.
  4.2 Execute o seguinte comando: Get-ExecutionPolicy
  4.3 Se retornar "Restricted", execute Set-ExecutionPolicy AllSignedou Set-ExecutionPolicy Bypass -Scope Process
  4.4 Agora execute o seguinte comando: "Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol =                             [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))"
  4.5 Aguarde alguns segundos para que o comando seja concluído.
  4.6 Se você não encontrar nenhum erro, está pronto para usar o Chocolatey!
  4.7 Execute o seguinte comando para ver se a versão do Chocolatey está instalada em sua máquina: choco -v
  4.8 Para instalar o Yarn (Instalar), execute o seguinte comando na linha de comando ou no PowerShell: "choco install yarn"
  4.9 Execute o seguinte comando para ver se a versão do yarn está instalada em sua máquina: yarn -v
  4.10 Para instalar o Node JS (Instalar), execute o seguinte comando na linha de comando ou no PowerShell: "choco install nodejs.install"
  4.11 Execute o seguinte comando para ver se a versão do Node está instalada em sua máquina: node -v
  
5. Depois de tudo instalado executar o seguinte comando no PowerShell ou CMD, ele irá abrir o Visual Studio Code: "code ."
  5.1 Ir em Source Code Control: 4º Icone que fica no painel lateral Esquerdo do Visual Studio code
  5.2 clicar em clonar repositorio e adicionar o Link "https://github.com/Brunolisboa/Podcastr.git" e dar um Enter
6. Abrir o terminal com as teclas: Ctrl + " 
  6.1 executar os seguintes comandos para inicializar o server mockado: "yarn server", caso de erro na inicialização do servidor executar o seguinte comando "yarn add jason-           server -D" e depois o "yarn server".
  6.2 depois de executado e server abrir outro terminal e digitar: "yarn dev".
  6.3 abrir o navegador e digitar na barra de pesquisa a seguinte url: "http://localhost:3000/"
  6.4 Pronto! Projeto inicializado.
  
## Tecnologias utilizadas no Projeto 
![](/imgs_git/stacks.jpg)

## Página Home em execução 
![](/imgs_git/PodcastrHome.jpg)

## Página do Episódio em execução
![](/imgs_git/PodcastrEpisode.jpg)


