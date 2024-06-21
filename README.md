# argocd-multiple-sources-tutorial

```
helm repo list
```

```
helm search repo prometheus-community  

NAME                                                    CHART VERSION   APP VERSION     DESCRIPTION                                       
prometheus-community/alertmanager                       1.11.0          v0.27.0         The Alertmanager handles alerts sent by client ...
prometheus-community/alertmanager-snmp-notifier         0.3.0           v1.5.0          The SNMP Notifier handles alerts coming from Pr...
prometheus-community/jiralert                           1.7.1           v1.3.0          A Helm chart for Kubernetes to install jiralert   
prometheus-community/kube-prometheus-stack              60.3.0          v0.74.0         kube-prometheus-stack collects Kubernetes manif...
prometheus-community/kube-state-metrics                 5.20.0          2.12.0          Install kube-state-metrics to generate and expo...
prometheus-community/prom-label-proxy                   0.8.0           v0.10.0         A proxy that enforces a given label in a given ...
prometheus-community/prometheus                         25.22.0         v2.53.0         Prometheus is a monitoring system and time seri...
prometheus-community/prometheus-adapter                 4.10.0          v0.11.2         A Helm chart for k8s prometheus adapter           
prometheus-community/prometheus-blackbox-exporter       8.17.0          v0.25.0         Prometheus Blackbox Exporter                      
prometheus-community/prometheus-cloudwatch-expo...      0.25.3          0.15.5          A Helm chart for prometheus cloudwatch-exporter   
prometheus-community/prometheus-conntrack-stats...      0.5.10          v0.4.18         A Helm chart for conntrack-stats-exporter         
prometheus-community/prometheus-consul-exporter         1.0.0           0.4.0           A Helm chart for the Prometheus Consul Exporter   
prometheus-community/prometheus-couchdb-exporter        1.0.0           1.0             A Helm chart to export the metrics from couchdb...
prometheus-community/prometheus-druid-exporter          1.1.0           v0.11.0         Druid exporter to monitor druid metrics with Pr...
prometheus-community/prometheus-elasticsearch-e...      5.8.1           v1.7.0          Elasticsearch stats exporter for Prometheus       
prometheus-community/prometheus-fastly-exporter         0.3.0           v7.6.1          A Helm chart for the Prometheus Fastly Exporter   
prometheus-community/prometheus-ipmi-exporter           0.4.0           v1.8.0          This is an IPMI exporter for Prometheus.          
prometheus-community/prometheus-json-exporter           0.11.1          v0.6.0          Install prometheus-json-exporter                  
prometheus-community/prometheus-kafka-exporter          2.10.0          v1.7.0          A Helm chart to export the metrics from Kafka i...
prometheus-community/prometheus-memcached-exporter      0.3.2           v0.14.3         Prometheus exporter for Memcached metrics         
prometheus-community/prometheus-modbus-exporter         0.1.2           0.4.1           A Helm chart for prometheus-modbus-exporter       
prometheus-community/prometheus-mongodb-exporter        3.5.0           0.40.0          A Prometheus exporter for MongoDB metrics         
prometheus-community/prometheus-mysql-exporter          2.5.3           v0.15.1         A Helm chart for prometheus mysql exporter with...
prometheus-community/prometheus-nats-exporter           2.17.0          0.15.0          A Helm chart for prometheus-nats-exporter         
prometheus-community/prometheus-nginx-exporter          0.2.1           0.11.0          A Helm chart for the Prometheus NGINX Exporter    
prometheus-community/prometheus-node-exporter           4.36.0          1.8.1           A Helm chart for prometheus node-exporter         
prometheus-community/prometheus-opencost-exporter       0.1.1           1.108.0         Prometheus OpenCost Exporter                      
prometheus-community/prometheus-operator                9.3.2           0.38.1          DEPRECATED - This chart will be renamed. See ht...
prometheus-community/prometheus-operator-admiss...      0.13.0          0.74.0          Prometheus Operator Admission Webhook             
prometheus-community/prometheus-operator-crds           12.0.0          v0.74.0         A Helm chart that collects custom resource defi...
prometheus-community/prometheus-pgbouncer-exporter      0.3.0           v0.8.0          A Helm chart for prometheus pgbouncer-exporter    
prometheus-community/prometheus-pingdom-exporter        2.5.0           20190610-1      A Helm chart for Prometheus Pingdom Exporter      
prometheus-community/prometheus-pingmesh-exporter       0.4.0           v1.2.1          Prometheus Pingmesh Exporter                      
prometheus-community/prometheus-postgres-exporter       6.0.0           v0.15.0         A Helm chart for prometheus postgres-exporter     
prometheus-community/prometheus-pushgateway             2.13.0          v1.8.0          A Helm chart for prometheus pushgateway           
prometheus-community/prometheus-rabbitmq-exporter       1.11.0          v0.29.0         Rabbitmq metrics exporter for prometheus          
prometheus-community/prometheus-redis-exporter          6.2.0           v1.58.0         Prometheus exporter for Redis metrics             
prometheus-community/prometheus-smartctl-exporter       0.10.0          v0.12.0         A Helm chart for Kubernetes                       
prometheus-community/prometheus-snmp-exporter           5.4.0           v0.26.0         Prometheus SNMP Exporter                          
prometheus-community/prometheus-sql-exporter            0.1.0           v0.5.4          Prometheus SQL Exporter                           
prometheus-community/prometheus-stackdriver-exp...      4.5.0           v0.15.0         Stackdriver exporter for Prometheus               
prometheus-community/prometheus-statsd-exporter         0.13.1          v0.26.1         A Helm chart for prometheus stats-exporter        
prometheus-community/prometheus-systemd-exporter        0.2.2           0.6.0           A Helm chart for prometheus systemd-exporter      
prometheus-community/prometheus-to-sd                   0.4.2           0.5.2           Scrape metrics stored in prometheus format and ...
prometheus-community/prometheus-windows-exporter        0.3.1           0.25.1          A Helm chart for prometheus windows-exporter      
```


```
helm search repo prometheus-community/prometheus --versions
```

 ```
 helm show values argo/argo-cd > values.yaml
 ```
 