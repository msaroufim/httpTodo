#RESTful TODO list in node.js.

Really no surprises here, implementing the usual GET POST DELETE and PUT...

Probably not the most practical of todolists but hey to each his own!

##Usage

```
node httpToDo.js
```


```
server.listen(3000);
console.log('server listening on port 3000')
console.log('Add items: curl -d \'your todo item \' http://localhost:3000')
console.log('Get all items: curl http://localhost:3000')
console.log('Delete i\'th item: curl -d \'your todo item \' http://localhost:3000/i')
console.log('Update items: curl -d \'your new todo item \' http://localhost:3000/i')
```

