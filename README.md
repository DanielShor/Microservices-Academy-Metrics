# Microservices-Academy-Metrics

## Helm charts

### Prometheus Operator 
```
helm fetch stable/prometheus-operator
tar -xvzf .\prometheus-operator-8.7.0.tgz
```
### Prom MDM Converter
```
helm repo add sharedinfra http://chartmuseum.aires.ms
helm fetch sharedinfra/prom-mdm-converter
tar -xvzf .\prom-mdm-converter-0.1.5.tgz
```