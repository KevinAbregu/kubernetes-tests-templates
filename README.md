# kubernetes-tests-templates
Public image: 
currency-exchange: in28min/mmv2-currency-exchange-service:0.0.12-SNAPSHOT
currency-conversion: in28min/mmv2-currency-conversion-service:0.0.12-SNAPSHOT

Currency-exchange: port 8000
Currency-conversion: port 8100 (dependency of configmap with currency-exchange --> See /demo-loadbalancer-service/config-map-conversion.yaml
