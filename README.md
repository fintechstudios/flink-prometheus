# Flink Prometheus

Based on this [blog post](https://flink.apache.org/features/2019/03/11/prometheus-monitoring.html)
and [this repo](https://github.com/mbode/flink-prometheus-example), thanks to @mbode!

A very simple Flink image for configuring the Prometheus Metrics
reporter as the default reporter, and adds the necessary libs to the classpath.

Built on [the official Flink image](https://hub.docker.com/_/flink).

You will still need to add the `metrics.reporter.prom.port` field to your
Flink configuration and configure Prometheus to scrape from it as well.
