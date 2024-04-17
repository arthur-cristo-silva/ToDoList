<h1 align="center">
  TO DO List
</h1>

## Tecnologias
- Java Spring
- MySQL

## API Endpoints
- Create
```
$ POST localhost:8080/todos
{
	"name": "Todo1",
	"descricao": "Desc da Todo1",
	"realizado": false,
	"prioridade": 1
}
Criará a "Todo1" e à armazenará no banco de dados.
```
- Read
```
$ GET localhost:8080/todos
Retornará a lista de tarefas.
```
- Update
```
$ PUT localhost:8080/todos
{
	"name": "Todo1",
	"descricao": "Desc da Todo1",
	"realizado": true,
	"prioridade": 0
}
Irá atualizar a Todo1.
```
- Delete
```
$ POST localhost:8080/1
Irá remover a tarefa de ID 1.
```
