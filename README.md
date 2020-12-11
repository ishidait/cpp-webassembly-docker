# cpp-webassembly-docker

# Required tools

- Docker version 19.03.13+
- docker-compose version 1.27.4+

## Build docker image

```
> ./build.sh
```

## Run bash in the container

```
> ./run_bash.sh
```

## Hello World test in the container

```
> cd hello/build
> cmake ..
> cmake --build .
> ./hello
```

## JPEG -> WEBP Conversion in the browser using WebAssembly

```
> cd webp
> ./compile.sh
> ./serve.sh
```

Open your browser and go to http://localhost:5000
