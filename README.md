# docker-bazel
Run bazel in docker

## Usage

```bash
# run directly
docker run --rm -v $PWD:/usr/app tennyzhuang/bazel bazel [YOUR BAZEL COMMAND]

# interactive
docker run -it -v $PWD:/usr/app tennyzhuang/bazel bash
$ # Your bazel command
```
