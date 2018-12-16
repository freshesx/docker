# freshes/node

Install Node, Yarn and chinese mirrors.

This docker package use node LTS version, and set some chinese mirrors.

### Open workspace
``` bash
docker run --rm -it -v $(pwd):/workspace freshes/node:10.14 bash
```

### More usage
``` bash
docker run --rm -it -v $(pwd):/workspace freshes/node:10.14 sh -c 'yarn && yarn run build'
```
