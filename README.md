# node-ipc protestware docker container test

Please read my blog post [node-ipc-potestware](https://www.massimonicolardi.it/blog/10-node-ipc-protestware.html) to get info about the [CVE-2022-23812](https://gist.github.com/MidSpike/f7ae3457420af78a54b38a31cc0c809c)

This repo is a container to test how the [node-ipc] protestware code works.
The code has been sanitized and you can use this docker container to test it without installing anything.

## Installing

Open this repo in vscode and open it in the docker container using "open in remote container"

After this you are in a safe environment and you can run 

```js 
nom start
```

This is a SAFE simulation so no file will be overwritten at all.

