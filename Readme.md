Reproducible repository for: https://github.com/rubygems/rubygems/issues/4123

To reproduce you can execute:

```
docker run --rm -it -v $PWD:/src ruby:2.5 /src/platform-bug

docker run --rm -it -v $PWD:/src ruby:2.6 /src/platform-bug

docker run --rm -it -v $PWD:/src ruby:2.7 /src/platform-bug
```
