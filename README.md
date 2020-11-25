# Hello World

A tiny and simple Docker image rendering simple reponse on port 8000.

```bash
$ docker images | grep hello-world
REPOSITORY               TAG      IMAGE ID        CREATED           VIRTUAL SIZE
armsultan/hello-world    latest   15d53731c307    19 seconds ago    1.23MB
```

## Usage

1. Start a web server on port 80

```bash
$ docker run -d --rm --name hello-world -p 80:8000 armsultan/hello-world
```

2. `curl` or do other things

```
__                  __  __                     
|  \                |  \|  \                    
| $$____    ______  | $$| $$  ______            
| $$    \  /      \ | $$| $$ /      \           
| $$$$$$$\|  $$$$$$\| $$| $$|  $$$$$$\          
| $$  | $$| $$    $$| $$| $$| $$  | $$          
| $$  | $$| $$$$$$$$| $$| $$| $$__/ $$          
| $$  | $$ \$$     \| $$| $$ \$$    $$          
 \$$   \$$  \$$$$$$$ \$$ \$$  \$$$$$$           

                                   __        __ 
                                  |  \      |  \
 __   __   __   ______    ______  | $$  ____| $$
|  \ |  \ |  \ /      \  /      \ | $$ /      $$
| $$ | $$ | $$|  $$$$$$\|  $$$$$$\| $$|  $$$$$$$
| $$ | $$ | $$| $$  | $$| $$   \$$| $$| $$  | $$
| $$_/ $$_/ $$| $$__/ $$| $$      | $$| $$__| $$
 \$$   $$   $$ \$$    $$| $$      | $$ \$$    $$
  \$$$$$\$$$$   \$$$$$$  \$$       \$$  \$$$$$$$

```