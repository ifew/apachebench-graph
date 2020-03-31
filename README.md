# ApacheBench execution and output to graph image

## Install ApacheBench

On mac:

```shell
brew install gnuplot
```

On linux:

```shell
sudo apt-get install gnuplot
```

## How to use

Run ApacheBench

```shell
ab -n 1000 -c 200 -g out.data http://website.com/
```

Run Plot graph

```shell
gnuplot plot.p
```
