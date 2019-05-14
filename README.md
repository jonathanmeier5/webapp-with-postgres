# webapp-with-postgres
Quick &amp; dirty docker compose config for a webapp and a container to run them in.


If you check out this version of the [dockerfile](https://github.com/jonathanmeier5/webapp-with-postgres/commit/0266f55afb7732a32745d945af2d6117e60367eb), you can find a full blown DinD in container.

To launch docker and get a shell, run:
```
$ docker-compose -f docker-compose.my-test-container.yml run --rm sh
$ dockerd &
$ docker-compose -f docker-compose.my-app-containers.yml up
```
