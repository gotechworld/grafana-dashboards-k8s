![logo](https://raw.githubusercontent.com/dotdc/media/main/grafana-dashboards-kubernetes/kubernetes-grafana-dashboards-logo.png)

## Description

This repository contains a modern set of [Grafana](https://github.com/grafana/grafana) dashboards for [Kubernetes](https://github.com/kubernetes/kubernetes).\
They are inspired by many other dashboards from `kubernetes-mixin` and `grafana.com`.

You can also find and download them on [Grafana.com](https://grafana.com/grafana/dashboards/?plcmt=top-nav&cta=downloads&search=dotdc).

## Features

Theses dashboards are made and tested for the [kube-prometheus-stack](https://github.com/prometheus-community/helm-charts/tree/main/charts/kube-prometheus-stack) chart, but they should work well with others as soon as you have [kube-state-metrics](https://github.com/kubernetes/kube-state-metrics) and [prometheus-node-exporter](https://github.com/prometheus/node_exporter) installed on your Kubernetes cluster.

## Dashboards

| File name                  | Description | Screenshot |
|:---------------------------|:------------|:----------:|
| k8s-addons-starboard-operator.json | Dashboard for the Starboard Operator from Aqua Security. | [LINK](https://raw.githubusercontent.com/dotdc/media/main/grafana-dashboards-kubernetes/k8s-addons-starboard-operator.png) |
| k8s-system-api-server.json | Dashboard for the API Server Kubernetes. | [LINK](https://raw.githubusercontent.com/dotdc/media/main/grafana-dashboards-kubernetes/k8s-system-api-server.png) |
| k8s-system-coredns.json    | Show information on the CoreDNS Kubernetes component. | [LINK](https://raw.githubusercontent.com/dotdc/media/main/grafana-dashboards-kubernetes/k8s-system-coredns.png) |
| k8s-views-global.json      | `Global` level view dashboard for Kubernetes. | [LINK](https://raw.githubusercontent.com/dotdc/media/main/grafana-dashboards-kubernetes/k8s-views-global.png) |
| k8s-views-namespaces.json  | `Namespaces` level view dashboard for Kubernetes. | [LINK](https://raw.githubusercontent.com/dotdc/media/main/grafana-dashboards-kubernetes/k8s-views-namespaces.png) |
| k8s-views-nodes.json       | `Nodes` level view dashboard for Kubernetes. | [LINK](https://raw.githubusercontent.com/dotdc/media/main/grafana-dashboards-kubernetes/k8s-views-nodes.png) |
| k8s-views-pods.json        | `Pods` level view dashboard for Kubernetes. | [LINK](https://raw.githubusercontent.com/dotdc/media/main/grafana-dashboards-kubernetes/k8s-views-pods.png) |

### Install manually

On the WebUI of your Grafana instance, put your mouse over the `+` sign on the left menu, then click on `Import`.\
Once you are on the Import page, you can upload the JSON files one by one from your local copy using the `Upload JSON file` button.

### Install via grafana.com

On the WebUI of your Grafana instance, put your mouse over the `+` sign on the left menu, then click on `Import`.\
Once you are on the Import page, you can put the grafana.com dashboard id (see table bellow) under `Import via grafana.com` then click on the `Load` button. Repeat for each dashboard.

Grafana.com dashboard id list:

| Dashboard                          | ID    |
|:-----------------------------------|:------|
| k8s-addons-starboard-operator.json | 16337 |
| k8s-system-api-server.json         | 15761 |
| k8s-system-coredns.json            | 15762 |
| k8s-views-global.json              | 15757 |
| k8s-views-namespaces.json          | 15758 |
| k8s-views-nodes.json               | 15759 |
| k8s-views-pods.json                | 15760 |
