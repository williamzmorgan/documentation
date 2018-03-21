# Service folder

A service must have its own folder.

The only mandatory file is the `mesg.yml` that contains all the service definitions. See [service file](/./service/develop/service-file.md) page.

```
|-- SERVICE_NAME
|   |-- .env
|   |-- .git/
|   |-- .gitignore
|   |-- .mesg
|   |-- .mesgignore
|   |-- mesg.yml
|   |-- Dockerfile
|   |-- source/
|   |   |-- main.go
```


