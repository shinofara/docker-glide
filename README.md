docker-glide
===============

alpine 3.4


## Usage

```
$ docker run --rm -t \
    -v /path/to/src/dir:/work \
    shinofara/docker-glide:<version> <commnad>
```

### Example

```
$ docker run --rm -t \
    -v ${pwd}:/work \
    shinofara/docker-glide:latest up
```