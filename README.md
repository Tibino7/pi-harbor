# pi-harbor
Harbor integration on pi-k3s cluster

This chart is a custom variation of official harbor chart from [goharbor.io](https://goharbor.io) .
The main variations are the usage of arm64 images for each component, and a simpler ingress management for a classic nginx ingress controller.

This helm chart is currently used to monitor my k3s cluster on 5 raspberry pi machines. 
