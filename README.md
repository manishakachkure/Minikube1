#What is Minikube? Minikube is a tool that makes it easy to run Kubernetes locally. Minikube runs a single-node Kubernetes cluster inside a VM on your laptop for users looking to try out Kubernetes or develop with it day-to-day. Installation macOS brew cask install minikube Linux  curl -LO https://storage.googleapis.com/minikube/releases/latest/mi…

Minikube Features

    Minikube supports Kubernetes features such as:
        DNS
        NodePorts
        ConfigMaps and Secrets
        Dashboards
        Container Runtime: Docker, rkt, CRI-O and containerd
        Enabling CNI (Container Network Interface)
        Ingress
  
 Q. Does Minikube requires docker?
  Minikube creates a Virtual Machine that includes Kubernetes and a Docker daemon. When Kubernetes attempts to schedule containers using Docker, the Docker daemon may require external network access to pull containers. If you are behind an HTTP proxy, you may need to supply Docker with the proxy settings. 
