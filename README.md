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
##### falha na autencicacao ! 401
caso essa resposta ocorra ,  significa que ocorreu uma falha no processo de autenticação requisicao , motivo  token 
invalido ou expirado 
