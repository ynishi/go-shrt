# go-shrt
A command runner like alias

Reusable command management is
* history
* alias
* task runner

New command management is requied 
* Easy to add commands, manage, execute from everywhere.
* Simple template for development.

## Usage
```
shrt ${app} ${cmd} -- ${args}  
# excute commands 
```
```
# shrt.yml in $HOME
apps:
  app1: 
    init:
      cmds:
        - ...
    run:
      cmds:
        - ...
```

## Template
* Sample template is written with go-task's Taskfile format.
* https://github.com/go-task/task

## LICENSE
* MIT, see LICENSE
