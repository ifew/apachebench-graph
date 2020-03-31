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
gnuplot graph.p
```

or Run Plot Time Series

```shell
gnuplot timeseries.p
```



### Reference

- Graph https://memorynotfound.com/using-gnuplot-to-plot-apache-benchmark-data/
- Time Series http://www.bradlanders.com/2013/04/15/apache-bench-and-gnuplot-youre-probably-doing-it-wrong/