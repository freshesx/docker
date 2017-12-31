# freshes/yarn

<p>
  <img src="http://dockeri.co/image/freshes/yarn"></img>
</p>

Designed for freshes applications. Configure node environment, and set china mirrors.

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
