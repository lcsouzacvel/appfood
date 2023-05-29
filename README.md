## Dentro do diretorio do projeto node 

1º npm install

2º npm i -g yarn

3° docker run -p 27017:27017 -d mongo

4° yarn dev

redirecionando o mongo db com o docker
docker run --name “nome do banco” --volume /save/mongo:/data/db -p 27017:27017 -d mongo 
docker run --name mongo --volume /save/mongo:/data/db -p 27017:27017 -d mongo
