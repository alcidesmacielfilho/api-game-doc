# api-game-doc
esta api é para estudo 
## endponts
### GET /games
este endpont é responsável de carregar todos os games cadastrados
#### parametros recebidos
nenhum
#### respostas 
##### ok ! 200
caso essa resposta ocorra você receberá a listagem de todos os games

exemplo
```
 {
        "id": 25,
        "title": " a volta dos que nao foram",
        "year": 2018,
        "price": 45
    },
    {
        "id": 26,
        "title": "sem chamada  wm",
        "year": 2020,
        "price": 50
    }
    ```
##### falha na autencicacao ! 401
caso essa resposta ocorra ,  significa que ocorreu uma falha no processo de autenticação requisicao , motivo  token 
invalido ou expirado 

### PUT /auth
este endpont é responsável de validar  o usuario para acesso ao sistema
#### parametros recebidos
 email ; email do usuario
 password : senha do usuario
 exemplo:
```
{
 "email" : "alcides@estudo.com.br" ,
 "password" : "nodes<3"
}
```

#### respostas 
##### ok ! 200
caso essa resposta ocorra você receberá a listagem de todos os games

exemplo
##### falha na autencicacao ! 401
caso essa resposta ocorra ,  significa que ocorreu uma falha no processo de autenticação requisicao , motivo  senha ou email incorreto

