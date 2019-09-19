# Example SSE Angular and Node Apps with Bazel

This project uses [bazel](https://bazel.build/) and
[angular-cli](https://github.com/angular/angular-cli).

Its purpose is to demonstrate techniques for working with streaming data flow in
an Angular application. Its data comes from a server which generates fake
foreign currency exchange data. This project is a Bazel monorepo that contains
both the Angular client and the Node server.

## Running

First start the server in one terminal:

```
yarn
yarn start:server
```

Then, in a new terminal, start the client:

```
yarn start:client
```

<http://localhost:4200/>

## Useful Links:

[RxJS 6 Documentation](http://reactivex.io/rxjs/)

## Contact

Author:

Kyle Cordes, @kylecordes, <http://kylecordes.com>

Angular Boot Camp training:

<https://angularbootcamp.com/>

Our blog:

<http://blog.oasisdigital.com/>

Our other services:

<http://oasisdigital.com/>
