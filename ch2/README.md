# Kubernetes 安裝方法
+ Kubernetes 可安裝至不同的作業系統平台！
+ 可安裝於虚擬機上，進行自我練習！
## 將 Kubernetes 安裝在 VirtualBox 的 VM 上
+ VM 上安裝 CentOS 8 Stream 版本的 Linux
+ 使用 CRI-O 輕量級容器取代 Docker 地位
+ 使用三部 VM：

|主機名稱|IP位置|
|:---|:---|
|k8smaster|10.0.0.1/24|
|k8snode1|10.0.0.2/24|
|k8snode2|10.0.0.3/24|

### 安


#### 參考文獻
+ [Install Kubernetes 1.21.1 on Centos 8 Stream](https://medium.com/twodigits/install-kubernetes-1-21-1-on-centos-8-stream-include-fix-cap-perfmon-acf23a6879c6)
+ [CRI-O as a replacement for Docker as the runtime for Kubernetes: setting up on CentOS 8](https://prog.world/cri-o-as-a-replacement-for-docker-as-the-runtime-for-kubernetes-setting-up-on-centos-8/)
+ [Install and Set Up kubectl on Windows](https://kubernetes.io/docs/tasks/tools/install-kubectl-windows/)
+ [Install and Set Up kubectl on Linux](https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/)
+ [Install and Set Up kubectl on macOS](https://kubernetes.io/docs/tasks/tools/install-kubectl-macos/)
+ [How to install Kubernetes on Windows 10](https://dev.to/devcrafter91/how-to-install-kubernetes-on-windows-10-55b6)
+ [Kubernetes on CRI-O](https://dev.to/abhivaidya07/kubernetes-on-cri-o-centos-o1m)
+ [CRI-O Installation Instructions](https://github.com/cri-o/cri-o/blob/master/install.md)
+ [Install CRI-O Container Runtime on CentOS 8 / CentOS 7](https://computingforgeeks.com/install-cri-o-container-runtime-on-centos-linux/)
+ [使用CRI-O 和 Kubeadm 搭建高可用 Kubernetes 集群](https://xujiyou.work/%E4%BA%91%E5%8E%9F%E7%94%9F/CRI-O/%E4%BD%BF%E7%94%A8CRI-O%E5%92%8CKubeadm%E6%90%AD%E5%BB%BA%E9%AB%98%E5%8F%AF%E7%94%A8%20Kubernetes%20%E9%9B%86%E7%BE%A4.html)
