#RESTful TODO list in node.js.

Really no surprises here, implementing the usual GET POST DELETE and PUT...

Probably not the most practical of todolists but hey to each his own!

##Usage

Get the server listening

```
node httpToDo.js
```


```
curl -d \'your todo item \' http://localhost:3000'
curl http://localhost:3000'
curl -d \'your todo item \' http://localhost:3000/i'
curl -d \'your new todo item \' http://localhost:3000/i'
```

