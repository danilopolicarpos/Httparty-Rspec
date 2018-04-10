#  Httparty + Rspec

Abra o terminal e execute o comando abaixo :
```
bundle install      
```

Vamos instalar  o servidor Json-server:
```
npm install -g json-server
```
Agora vamos rodar o servidor Json-Server:

```
json-server --watch endpoints.json
````

O resultado será esse: 
```
\{^_^}/ hi!

Loading db.json
Done

Resources
http://localhost:3000/clientes

Home
http://localhost:3000

Type s + enter at any time to create a snapshot of the database
Watching...

```

## Executando os testes

Abra uma nova aba e digite o comando abaixo:

```
rspec spec/crud.rb 
```

