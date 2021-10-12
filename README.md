# flannel

Flannelは、レイヤー3通信を保証する、Kubernetesのためのオーバレイネットワークリソースです。   
AIONでは、主にエッジコンピューティング環境において Kubernetes / AION にレイヤー3通信を実装するために、また、マイクロサービス間の通信を行うために、Flannelを採用しています。

# flannelのデプロイ方法  
以下のコマンドで、Flannelをデプロイしてください。
```
kubectl apply -f https://raw.githubusercontent.com/coreos/flannel/2140ac876ef134e0ed5af15c65e414cf26827915/Documentation/kube-flannel.yml
```