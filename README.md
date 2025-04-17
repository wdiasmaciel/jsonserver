# jsonserver

`
npm install -g json-server --save
`


`
npm install -g json-server
`


`
npm install json-server
`


`
**npx json-server --watch db/db.json --port 333**
`

`

`
**json-server --watch db/db.json --port 3333** 
`


`
json-server --watch db/db.json --port 3333
`



```
  Entrar no Replit (https://replit.com/).
  Clicar no botão "+ Create App".
  Clicar na aba "Chose a Template".
  Selecionar a opção "Node.js".
  No campo "Title", informar o nome do projeto de vocês: PetMatch.
  Em "Privacy", manter como "Public".
  Clicar no botão "+ Create App".
  Clicar no ícone "Open Files" (canto superior direito).
  Clicar no ícone dos 3 pontinhos e clicar em "New Folder". Criar uma nova pasta com o nome "db".
  Clicar novamente no ícone dos 3 pontinhos e clicar em "New File". Criar o arquivo db.json dentro da pasta db.
  Colocar o JSON de vocês dentro do arquivo db.json. Exemplo:
  {
    "cidades": [
      {"id": 1, "cidade": "Belo Horizonte", "estado": "MG", "população": 3800000},
      {"id": 2, "cidade": "São Paulo", "estado": "SP", "população": 11800000},
      {"id": 3, "cidade": "Rio de Janeiro", "estado": "RJ", "população": 5300000},
      {"id": 4, "cidade": "Curitiba", "estado": "PR", "população": 1200000},
      {"id": 5, "cidade": "Fortaleza", "estado": "CE", "população": 2100000}
    ]
  }

  Clicar no ícone "All tools" (4 quadradinhos na barra vertical no canto esquerdo).
  Clicar na opção "Shell".
  Na linha de comando do "Shell", digitar os comandos abaixo, digitando <ENTER> ao final de cada um deles:

  npm install -g json-server --save
  npx json-server --watch db/db.json

  Nesse momento, o Replit abrirá uma janela de "Preview" em que serão apresentados os "endpoints" para acesso ao seu JSON. No caso do meu exemplo, será "/cidades". Nessa janela, também será apresentado o link (verde) e o QRCode para acesso aos "endpoints".


    petcmatch.json:
    {
      "pets": [
         {"id": 1, "nome": "pet1", ...},
         {"id": 2, "nome": "pet2", ...},
      ],
      "messages": [
         {"id": 1, "title": "title1", "body": "body1", ...},
         {"id": 2, "title": "title2", "body": "body2", ...},
      ],
      "notification": [
         {"id": 1, "title": "title1", "body": "body1", ...},
         {"id": 2, "title": "title2", "body": "body2", ...},
      ]
    }

```