## API DevsNotes Laravel 8.0

API para CRUD de lista de tarefas.

EndPoints 

- http://server/api/notes -> GET sem parâmetros;
- http://server/api/note/{id} -> GET parâmetro: id;
- http://server/api/note -> POST parâmetros: id,title,body;
- http://server/api/note/{id} -> PUT parâmetros: id,title,body;
- http://server/api/note/{id} -> DELETE parâmetro: id;

Base de Dados:

1-) Criar base MySql com nome "devsnotes"

2-) Importar arquivo "/notes.sql"

Recomendação para teste da api:
https://resttesttest.com/
