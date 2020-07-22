# ONG App

<h1 align="center" >
    <img src="./frontend/src/assets/logo.svg" />
</h1>

Essa é uma aplicação que usa JavaScript como linguagem principal com o objetivo de desenvolver um sistema para ONG's. O sistema consiste, basicamente, de uma aplicação web conectada a um app mobile que permite o cadastro de ONG's através do site que, por sua vez, cadastram casos onde será descrito a natureza de algum problema. Esses casos serão apresentados no app mobile para usuários que tem como objetivo contribuir de alguma forma para determinado caso de determinada ONG. A aplicação foi desenvolvida na Semana Omnistack 11.0 da Rocketseat como estudo.

<h1 align="center" >
    <img src="./demo/demo.gif"/>
</h1>

## **Tecnologias utilizadas:**
* JavaScript
* Node.JS
* React.JS
* React Native
* SQLite

## **Requisitos para uso a partir deste repositório:**
1. Node JS e npm instalados em sua máquina: **12.16.1 (Versão recomendada)**
* Para instalação do node utilize: `$ sudo apt update` e depois `$ sudo apt install nodejs`. Verifique a versão usando: `$ node -v`
* Para instalação do npm utilize: `$ sudo apt install npm`

2. yarn instalado em sua máquina
* Utilize o seguinte comando para instalação: `$ sudo apt install yarn`

## **Para execução do projeto:**

1. Baixe o atual repositório em sua máquina da maneira que preferir (3 modos abaixo):

* **Através do git:** copie o link do repositorio, abra seu terminal navegue até a pasta onde deseja hospedar o projeto e digite o comando: 
`$ git clone https://github.com/viniciussaturnino/ONGApp`

*  **Através de um fork desse repositório:** A direita do nome do repositório há um botão **fork**, clique nele e estará em seu perfil após esse processo. Repita os mesmos passos do item anterior usando o link do fork que estará em seu repositório

*  **Através de download do repositório:** A direita na pagina inicial do repositório há um botão verde **clone or download**, clique nele e faça o download em ZIP do projeto. Descompacte na pasta onde foi baixado.

2. Após clonar o repositório, navegue até a pasta do projeto usando `cd` e execute o comando `cd backend` para entrar na pasta do backend da aplicação. Em seguida execute `$ npm install`. Faça o mesmo no para o frontend.

3. Você precisará de **dois** terminais (um para execução do backend e outro para o frontend), em um deles navegue até a pasta do backend usando `cd`. Em seguida execute `$ npm start`. Faça o mesmo no **outro** terminal para o frontend.
Após executar o `$ npm start` no terminal do frontend você será redirecionado para a página web no seu navegador.

3. Para executar a parte mobile é necessário que tenha o app **"expo"** instalado no seu dispositivo (poderá obtê-lo na sua loja de apps). Após a obtenção do **"expo"** navegue até a pasta mobile do projeto em um outro terminal e execute `$ yarn start`, você será redirecionado para uma página na web. Espere alguns segundos até aparecer um QR Code na tela que deverá ser scaneado pela camera do seu dispositivo. Você sera redirecionado para o app expo com a aplicação mobile desse repositório.