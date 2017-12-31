# freshes/yarn

Designed for freshes applications.

This docker package use node 8.9 LTS version (Carbon). And set some chinese mirrors.

### Open workspace
``` bash
docker run --rm -it -v $(pwd):/workspace freshes/yarn bash
```

### Yarn build
``` bash
docker run --rm -it -v $(pwd):/workspace freshes/yarn yarn run build
```

### Yarn install and build
``` bash
docker run --rm -it -v $(pwd):/workspace freshes/yarn sh -c 'yarn && yarn run build'
```
