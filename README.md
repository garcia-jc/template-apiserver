## template-apiserver

This is an early stage, [Go project template](https://go.dev/blog/gonew) aimed to guide the project layout design 
for API projects. The intent is to complement the [Organizing a Go module guide](https://go.dev/doc/modules/layout) article, 
hopefully easing the learning curve for new Go engineers.


### Requirements

In order to use this template, you need to install the gonew tool. You can do that by running 
>  go install golang.org/x/tools/cmd/gonew@latest

### Usage

To use this template for a new project, you should run the following command in the terminal
> gonew github.com/garcia-jc/template-apiserver [YOUR MODULE NAME]

For example, if your new project module will be `github.com/garcia-jc/my-api-server`, then you should run 
> gonew github.com/garcia-jc/template-apiserver github.com/garcia-jc/my-api-server

This will create a folder `./my-api-server`, with a project skeleton ready to be used.

```
→ find ./my-api-server 

./my-api-server
./my-api-server/cmd
./my-api-server/cmd/server
./my-api-server/cmd/server/main.go
./my-api-server/go.mod
./my-api-server/LICENSE
./my-api-server/internal
./my-api-server/internal/config
./my-api-server/internal/config/config.go
./my-api-server/api
./my-api-server/api/handler.go
./my-api-server/api/types.go
./my-api-server/api/client
./my-api-server/api/client/client.go
./my-api-server/api/router.go
./my-api-server/api/errors.go
./my-api-server/service
./my-api-server/service/service.go
./my-api-server/service/types.go
```

### Demo

There is another repository, [garcia-jc/notes-apiserver](https://github.com/garcia-jc/notes-apiserver) that is a notes API server implementation, aimed to further illustrate the usage of this layout.
