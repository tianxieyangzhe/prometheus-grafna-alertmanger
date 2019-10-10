# prometheus-grafna-alertmanger
prometheus 采集etcd，docker，kubernetes，通过grafana展示并配置告警


# Prometheus Grafana AlterManager 介绍
# Grafana 与 Prometheus 集成
1. 配置数据源
2. 导入k8s-dashbord
3. 自定义 dashbord （ingress）
# Prometheus 集成 AlterManager
# 使用AlterManager 监视 IngressController
1. Ingress controller 注意事项
2. 配合 ruler （up）
3. 配置 邮件接收
# 对ETCD的监控
1. etcd 配置
2. etcd 的多个ruler
# 对Docker-Engine 的监控
1. 设置docker
2. 配置 ruler （up）
# 使用Kube-State-Metrics的数据
1. Kube-State-Metrics 数据的特点
2. 形成多个 ruler 
3. MetricBeta 接入
4. kibana dashbord 展示
# Prometheus 数据持久化
1. 自身数据存储
2. 配置InfluxDB
3. 使用Operator提高Prometheus可用性
