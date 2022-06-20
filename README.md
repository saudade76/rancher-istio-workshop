# Managing and Securing microservices with Rancher, Istio, and Neuvector

This repository contains provide the lab exercise guide for a hands-on workshop to help audience to understand and explore the open source technologies in managing and securing microservices-based applications running on Kubernetes.



## Open Source Technologies Used

| Software           | Version  | Remarks                                                      |
| ------------------ | -------- | ------------------------------------------------------------ |
| Rancher            | 2.6.4    | Enterprise-grade Kubernetes Management Platform              |
| RKE2               | 1.21.4   | Rancher Kubernetes Engine 2 - with Kubernetes version 1.21   |
| Prometheus/Grafana | 19.0.3   | Monitoring tools for Kubernetes                              |
| Istio              | 1.11.7   | Service Mesh with Istio distributed as part of Rancher       |
| Neuvector          | 5.0.0-b1 | The industry's first open source full-lifecycle cloud native security platform for Kubernetes |



## Lab Exercises

* Access to the lab environment
* [Deploy Monitoring and Istio onto RKE2 cluster](docs/Exercise-01-Deploy Monitoring and Istio on RKE2 Cluster.md)
* [Deploy Sample BookInfo Microservices](docs/Exercise-02-Deploy sample Bookinfo Microservices Application.md)
* [Traffic Canary Deployment](docs/Exercise-03-Traffic Shaping with Service Mesh.md)
* [Visualize Service Mesh with Kiali](docs/Exercise-04-Visualize Service Mesh with Kiali.md)
* [Explore Distributed Tracing with Jaeger](docs/Exercise-05-Explore Distributed Tracing with Jaeger.md)
* [A glimpse of NeuVector in how it secures Microservices](docs/Exercise-06-Explore NeuVector and how it secure Microservices.md)



## References

* [Rancher Documentation]()
* [Istio Documentation](https://istio.io/latest/docs/)
* [NeuVector Documentation](https://open-docs.neuvector.com/)



