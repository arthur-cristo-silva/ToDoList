<h1 align="center">
  TO DO List
</h1>

## Tecnologias
- Java Spring
- MySQL

## API Endpoints
- Create

Criará a "Todo1" e à armazenará no banco de dados.
```
$ POST localhost:8080/todos
{
	"name": "Todo1",
	"descricao": "Desc da Todo1",
	"realizado": false,
	"prioridade": 1
}
```
- Read

Retornará a lista de tarefas em ordem de prioridade.
```
$ GET localhost:8080/todos
```
- Update

Irá atualizar a Todo1.
```
$ PUT localhost:8080/todos
{
	"name": "Todo1",
	"descricao": "Desc da Todo1",
	"realizado": true,
	"prioridade": 0
}
```
- Delete

Irá remover a tarefa de ID 1.
```
$ POST localhost:8080/1
```
