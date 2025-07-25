<h1>Kubernetes Pod Design with Sidecar and Ambassador Patterns</h1>


<h2>Description</h2>
This project demonstrates advanced Kubernetes pod design using Sidecar and Ambassador patterns. It includes three multi-container pods: one with a Sidecar for log aggregation, another combining Nginx, a logging Sidecar, and an Ambassador for intra-pod communication, and a third with Nginx serving static content, log aggregation, and Prometheus metrics exposure.

<br />


<h2>Tools and Technologies</h2>

- Kubernetes
- Pod Patterns (Sidecar, Ambassador)
- kubectl
- YAML
- Nginx
- BusyBox

<h2>Project Walk-through</h2>

<p align="center">
Define a Kubernetes Pod using the Sidecar pattern <br />
<img src="https://i.postimg.cc/PxrFMpQr/1.jpg"/>
<br />
<br />
Deploy a Pod with Nginx, Sidecar, and Ambassador containers <br/>
<img src="https://i.postimg.cc/SKZH3fsz/2.jpg" />
<br />
<br />
Create an advanced Pod with Nginx, log aggregation, and Prometheus metrics <br/>
<img src="https://i.postimg.cc/pTC7zYNd/3.jpg"/>
<br />
<br />
Validate and Test advanced multi-container pod Functionality <br/>
<img src="https://i.postimg.cc/gcs99pTZ/4.jpg" />
<br />
<br />


</p>

