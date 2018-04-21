## docker-library
	
kubernetes 相关 images 同步
# 20180421
  gcr.io/google-containers/hyperkube:v1.9.7
  quay.io/calico/node:v2.6.8
  quay.io/calico/cni:v1.11.4
  quay.io/calico/routereflector:v0.4.2
  k8s.gcr.io/k8s-dns-kube-dns-amd64:1.14.10
  gcr.io/google_containers/heapster-amd64:v1.5.2

# 2018.03.24
  quay.io/coreos/hyperkube:v1.9.6_coreos.0
# 2018.03.21
  gcr.io/google_samples/k8skafka:v1
  gcr.io/google_samples/k8szk:v3
  prom/blackbox-exporter:v0.12.0

# 2018.03.02
  kubernetes-dashboard-amd64:v1.8.3
  kubernetes-helm/tiller:v2.8.1
  heapster-influxdb-amd64:v1.3.3

# 2018.02.09
  k8s.gcr.io/fluentd-elasticsearch:v2.0.4
# 2018.02.07
   giantswarm-tiny-tools:latest

# 2018.02.02
   cluster-proportional-autoscaler-amd64:1.1.2
   elasticsearch:v6.1.3
   tiller:v2.7.2

# 2018.01.20

	kubernetes-dashboard-amd64:v1.8.2
	metrics-server-amd64:v0.2.0

# 2018.01.12

	k8s-dns-sidecar-amd64:1.14.8
	k8s-dns-kube-dns-amd64:1.14.8
	k8s-dns-dnsmasq-nanny-amd64:1.14.8

# 2018.1.2017

* 新增监控组件heapster v1.5.0
	
	包括两个目录:heapster-amd64和addon-resizer(addon-resizer:1.8.1)

# 2017.12.24
* 将kube的4个组件版本升级到1.9.0
* 将本文采用markdown格式书写
	
# 2017.12.23
* 删除无关的目录
* 新增目录kube-aggregator-amd64
	  
# 2017.12.23

	kube-apiserver-amd64:v1.8.4
	kube-controller-manager-amd64:v1.8.4
	kube-scheduler-amd64:v1.8.4
	kube-proxy-amd64:v1.8.4
	etcd-amd64:3.0.17
	pause-amd64:3.0
	k8s-dns-sidecar-amd64:1.14.5
	k8s-dns-kube-dns-amd64:1.14.5
	k8s-dns-dnsmasq-nanny-amd64:1.14.5
	flannel:v0.9.1-amd64
