# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
store and manipulate data.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
model
```

Which layer in the MVC pattern communicates with the model?

```md
controller
```

Why don't we use views in our interpretation of the MVC pattern?

```md
// your response here
```

What does C.R.U.D stand for?

```md
Create, Read , Update , Delete
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
Controller
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
:index, :create, :update, :destroy, :show
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
- client send out 'GET' request for '/people/1' to rounter
- router translate the request and call show method in controller
- the show method will ask the person model to reponse the person with ID 1
- once show method recieved the data, it will translate to json and response back to client
```

What is the command to generate a new rails-api app?

```bash
rails-api new my_api
```

What is the command to start an instance of a rails server?

```bash
bin/rails server
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
- rake db:drop db:create db:migration db:test:prepare
- rake db:seed
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
// your response here
```
