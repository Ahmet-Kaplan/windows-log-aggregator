# Collecting Docker Log Files from DBs, Cloud Storages with Fluentd and Elasticsearch/OpenSearch

This directory contains the source files needed to make a Docker image
that collects Docker container log files using [Fluentd][fluentd]
and sends them to an instance of [Elasticsearch][elasticsearch] or Granafa Loki.

This image is designed to be used as part of the [Kubernetes][kubernetes] cluster bring up process. 

DB:
MS SQL (Sql Server)
MySQL
PostgreSQL
Mongo
TimescaleDB


Cloud:
AWS S3
Azure


This image has been extended to include FreeTDS to support the use of the mssql-lookup plugin and those 

fluent-plugin-concat
fluent-plugin-detect-exceptions
fluent-plugin-kubernetes_metadata_filter
fluent-plugin-kubernetes

fluent-plugin-multi-format-parser
fluent-plugin-systemd
fluent-plugin-filter-urldecode
fluent-plugin-rename-key
fluent-plugin-ua-parser

fluent-plugin-aws-elasticsearch-service
fluent-plugin-azurestorage-gen2
fluent-plugin-cloudwatch-logs
fluent-plugin-concat
fluent-plugin-datadog
fluent-plugin-elasticsearch
fluent-plugin-grafana-loki
fluent-plugin-forest
fluent-plugin-kafka
fluent-plugin-opensearch
fluent-plugin-prometheus
fluent-plugin-record-modifier
fluent-plugin-rewrite-tag-filter
fluent-plugin-route
fluent-plugin-s3
fluent-plugin-sqs
fluent-plugin-flowcounter
fluent-plugin-anonymizer

fluent-plugin-mssql-lookup
fluent-plugin-mongo
fluent-plugin-timescaledb
fluent-plugin-mysql
fluent-plugin-postgres

[fluentd]: http://www.fluentd.org/
[elasticsearch]: https://www.elastic.co/products/elasticsearch
[kubernetes]: https://kubernetes.io
