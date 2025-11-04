⚠️ **This setup is for learning and demo purposes — not production-ready as-is.**

# GitOps Hands-On with FluxCD and kind

This project demonstrates a complete **GitOps workflow** using **FluxCD** on a local Kubernetes cluster with **kind**.
It shows how to bootstrap Flux, connect it to a GitHub repository, deploy a sample application, and observe continuous reconciliation between Git and the cluster.

🔗 **Full write-up available on [Medium](https://medium.com/@rayanee/deploy-a-complete-gitops-workflow-with-fluxcd-3a8de9a3c7b2)**

---

## Prerequisites

Before you start, make sure you have the following installed:

* **Docker** (running)
* **kubectl** (to interact with the cluster)
* **kind** (to create a local Kubernetes cluster)
* **Git** (configured locally)
* **GitHub account** with a Personal Access Token (permission: `repo`)
* **Flux CLI** installed on your machine
