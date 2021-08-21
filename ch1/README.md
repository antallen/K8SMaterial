# Kuternets 基本結構認知
+ Kubernetes 是一個用於部署和管理容器的開源平台。
+ Kubernetes 是一個非常靈活和可擴展的平台。

## Kubernetes 架構和概念
+ Kubernetes 環境由控制面(control plane)(master)、用於保持集群狀態一致的分佈式存儲系統(distributed storage system)(etcd)和多個集群節點(cluster nodes)(Kubelets)組成。

![Kubernetes 架構概覽](1.jpg)
  + 圖片來源：https://platform9.com/blog/kubernetes-enterprise-chapter-2-kubernetes-architecture-concepts/

+ 控制面(control plane)是維護所有 Kubernetes 物件記錄的系統。

![Kubernetes 控制面分類圖](2.jpg)
  + 控制面由三個主要組件組成：kube-apiserver、kube-controller-manager和kube-scheduler。
  + 這些都可以在單個主節點上運行，也可以跨多個主節點(masters)複製以實現高可用性(High Availability)。
  + 