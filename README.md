
# RedHat's SP oTel collector 
for openshift clusters


[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/kubeblocks)](https://artifacthub.io/packages/search?repo=sp-otel-collector)


```
helm repo add sp-otel-collector https://geored.github.io/redhat_sp_otel_collector
helm repo update sp-otel-collector
helm upgrade --install sp-otel-collector sp-otel-collector --namespace resiliance-sp [ --create-namespace ]