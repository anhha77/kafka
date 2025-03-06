# Kafka

## Getting started

1. Run PV, PVC, Storageclass 
 - kubectl.exe apply -f kafka-pv.yaml
 - kubectl.exe apply -f kafka-pvc.yaml
 - kubectl.exe apply -f kafka-storageclass.yaml

2. Run Zookeeper 
 - kubectl.exe apply -f zookeeperDeploy.yaml

3. Run kafka Statefulset
 - kubectl.exe apply -f kafka-statefulset.yaml

3. Run kafka ui
 - kubectl.exe apply -f kafka-uiDeploy.yaml

