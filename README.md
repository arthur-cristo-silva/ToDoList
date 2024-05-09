# Lista de Tarefas
Uma API que gerencia lista de tarefas.

## Tecnologias Utilizadas
- **Java Spring**: Utilizado para criar o backend da aplicação.
- **MySQL**: Utilizado como banco de dados para armazenar as tarefas.

## Endpoints da API 
 
### Criar
Este endpoint criará uma nova tarefa chamada "Todo1" e a armazenará no banco de dados.
```bash
POST localhost:8080/todos
{
	"name": "Todo1",
	"descricao": "Desc da Todo1",
	"realizado": false,
	"prioridade": 1
}
```
## Ler 
Este endpoint retornará a lista de tarefas em ordem de prioridade.
```bash
$ GET localhost:8080/todos
```
## Atualizar 
Este endpoint atualizará a tarefa chamada “Todo1”.
```bash
$ PUT localhost:8080/todos
{
	"name": "Todo1",
	"descricao": "Desc da Todo1",
	"realizado": true,
	"prioridade": 0
}
```
## Delete
Este endpoint removerá a tarefa com ID 1.
```bash
$ DELETE localhost:8080/todos/1
```
