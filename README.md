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
  Entrar no GitHub (https://github.com/).
  Clicar no avatar de seu usuário (canto superior direito).
  Clicar na opção "Your repositories".
  Clicar no botão "New".
  Definir um nome para o repositório.
  Manter o repositório como público.
  Clicar na opção "Add a README file".
  Clicar no botão "Create repository".
  Ao abrir o VC Code em nuvem:
  Clicar no ícone "New Folder". Criar uma nova pasta com o nome "db".
  Clicar no ícone "New File". Criar o arquivo "db.json" dentro da pasta "db".
  Colocar o JSON de vocês dentro do arquivo "db.json". 
  Exemplo:
  {
    "cidades": [
      {"id": 1, "cidade": "Belo Horizonte", "estado": "MG", "população": 3800000},
      {"id": 2, "cidade": "São Paulo", "estado": "SP", "população": 11800000},
      {"id": 3, "cidade": "Rio de Janeiro", "estado": "RJ", "população": 5300000},
      {"id": 4, "cidade": "Curitiba", "estado": "PR", "população": 1200000},
      {"id": 5, "cidade": "Fortaleza", "estado": "CE", "população": 2100000}
    ]
  }

  Na linha de comando do terminal do VS Code, digitar os comandos abaixo, digitando <ENTER> ao final de cada um deles:

  npm install -g json-server --save
  npx json-server --watch db/db.json

  Nesse momento, o Codespaces apresentará os "endpoints" para acesso ao JSON. 
  No caso do meu exemplo, será "/cidades". 
  
  Exemplo para o caso do projeto PetMatch:
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