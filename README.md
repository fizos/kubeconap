# kubeconap

kubeconap是基于k8s的云原生容器云平台，功能方面旨在对齐kubesphere，整体采用前后端分离架构，后端内部采用基于go-grpc的微服务架构，目前项目持续开发中
初步计划包含入下几个组件：
web-console: web管理界面，采用vuejs3进行开发，nginx容器化部署；
api-server: rest api入口，充当api-gateway角色，采用nodejs技术栈, nodejs容器化部署；
kube-service: 原生k8s接入服务，采用client-go对接k8s集群，对接原生的k8s管理需求；
tenancy-service: 运管平台多租户管理功能