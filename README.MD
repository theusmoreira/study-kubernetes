## SVC - Service
- Abstração para expor aplicações executando em um ou mais pods
- Proveem IP'S fixos para comunicação
- Proveem um DNS para um ou mais pods
- São capazes de fazer balanceamento de carga
- Usamos labels

### Types
- ClusterIP
- NodePort
- LoadBalancer

## ConfigMap
 - Responsável por armazenar essas configurações que nós precisamos utilizar dentro de determinados pods, determinados recursos. Nós podemos guardar dentro deles para não acoplarmos o nosso recurso com informações de configuração, por isso um ConfigMap.

 ## ReplicaSets
 ## Deployments

 ## Volumes
 - Persistents Volumes
 - Persistent Volume Claim
 - Storage Classes
 