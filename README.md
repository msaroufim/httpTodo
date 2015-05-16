#RESTful TODO list in node.js.

Really no surprises here, implementing the usual GET POST DELETE and PUT...

Probably not the most practical of todolists but hey to each his own!

##Get Started

Get the server listening

```
node httpToDo.js
```

##Usage

Create a new entry in your todo list
```
curl -d \'your todo item \' http://localhost:3000'
```
Get all entries
```
curl http://localhost:3000'
```
Delete the i'th entry
```
curl -d \'your todo item \' http://localhost:3000/i'
```
Update the i'th entry
```
curl -d \'your new todo item \' http://localhost:3000/i'
```

