# Beats cookbook for app

This cookbook sets up filebeat and metricbeat on an instance. It is then called later in Packer as another cookbook. Filebeat and metricbeat are both data shippers. They can send data to Logstash, or straight to Elasticsearch.

Filebeat is a lightweight shipper for logs whereas Metricbeat is a lightweight shipper for metric data.

## Unit tests

To run the unit tests, enter the command:

```
chef exec rspec spec
```

## Integration tests

To run the integration tests, enter the command:

```
kitchen test
```

![Beats logo](https://cdn.worldvectorlogo.com/logos/elastic-beats.svg)
