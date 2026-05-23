# DevOps — Kubernetes

> Comprehensive collection of Kubernetes distributions, package management, cluster management, dashboards, service mesh, networking, security, autoscaling, operators, and debugging tools.

---

## Kubernetes Core & Distributions

| Repository | Description | Stars |
|------------|-------------|-------|
| [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) | Production-grade container orchestration — the source of truth | ![Stars](https://img.shields.io/github/stars/kubernetes/kubernetes?style=flat-square) |
| [k3s-io/k3s](https://github.com/k3s-io/k3s) | Lightweight K8s — edge, IoT, CI, ARM — single binary | ![Stars](https://img.shields.io/github/stars/k3s-io/k3s?style=flat-square) |
| [k0sproject/k0s](https://github.com/k0sproject/k0s) | Zero friction Kubernetes — single binary, any infra | ![Stars](https://img.shields.io/github/stars/k0sproject/k0s?style=flat-square) |
| [rancher/rke2](https://github.com/rancher/rke2) | Rancher's next-gen Kubernetes — security-focused | ![Stars](https://img.shields.io/github/stars/rancher/rke2?style=flat-square) |
| [kubernetes/minikube](https://github.com/kubernetes/minikube) | Run Kubernetes locally — multi-node support | ![Stars](https://img.shields.io/github/stars/kubernetes/minikube?style=flat-square) |
| [kubernetes-sigs/kind](https://github.com/kubernetes-sigs/kind) | Kubernetes in Docker — for local testing and CI | ![Stars](https://img.shields.io/github/stars/kubernetes-sigs/kind?style=flat-square) |
| [loft-sh/vcluster](https://github.com/loft-sh/vcluster) | Virtual Kubernetes clusters — lightweight multi-tenancy | ![Stars](https://img.shields.io/github/stars/loft-sh/vcluster?style=flat-square) |
| [canonical/microk8s](https://github.com/canonical/microk8s) | Low-ops, minimal production K8s — snap install | ![Stars](https://img.shields.io/github/stars/canonical/microk8s?style=flat-square) |
| [siderolabs/talos](https://github.com/siderolabs/talos) | Immutable Linux OS designed for Kubernetes | ![Stars](https://img.shields.io/github/stars/siderolabs/talos?style=flat-square) |
| [k3d-io/k3d](https://github.com/k3d-io/k3d) | Run K3s in Docker — fastest local K8s setup | ![Stars](https://img.shields.io/github/stars/k3d-io/k3d?style=flat-square) |

---

## Package Management & Configuration

| Repository | Description | Stars |
|------------|-------------|-------|
| [helm/helm](https://github.com/helm/helm) | The Kubernetes package manager — deploy complex apps with charts | ![Stars](https://img.shields.io/github/stars/helm/helm?style=flat-square) |
| [kubernetes-sigs/kustomize](https://github.com/kubernetes-sigs/kustomize) | Kubernetes-native configuration management — overlays, patches | ![Stars](https://img.shields.io/github/stars/kubernetes-sigs/kustomize?style=flat-square) |
| [helmfile/helmfile](https://github.com/helmfile/helmfile) | Declarative spec for deploying Helm charts | ![Stars](https://img.shields.io/github/stars/helmfile/helmfile?style=flat-square) |
| [helm/chart-testing](https://github.com/helm/chart-testing) | CLI for linting and testing Helm charts | ![Stars](https://img.shields.io/github/stars/helm/chart-testing?style=flat-square) |
| [bitnami/charts](https://github.com/bitnami/charts) | Bitnami Helm charts — 200+ production-ready charts | ![Stars](https://img.shields.io/github/stars/bitnami/charts?style=flat-square) |
| [cdk8s-team/cdk8s](https://github.com/cdk8s-team/cdk8s) | Define Kubernetes apps using programming languages | ![Stars](https://img.shields.io/github/stars/cdk8s-team/cdk8s?style=flat-square) |
| [stefanprodan/timoni](https://github.com/stefanprodan/timoni) | Package manager for Kubernetes — CUE-based configs | ![Stars](https://img.shields.io/github/stars/stefanprodan/timoni?style=flat-square) |

---

## Dashboards & UIs

| Repository | Description | Stars |
|------------|-------------|-------|
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | Official Kubernetes web UI | ![Stars](https://img.shields.io/github/stars/kubernetes/dashboard?style=flat-square) |
| [derailed/k9s](https://github.com/derailed/k9s) | Terminal UI to interact with Kubernetes clusters | ![Stars](https://img.shields.io/github/stars/derailed/k9s?style=flat-square) |
| [lensapp/lens](https://github.com/lensapp/lens) | Kubernetes IDE — most popular GUI for K8s | ![Stars](https://img.shields.io/github/stars/lensapp/lens?style=flat-square) |
| [headlamp-k8s/headlamp](https://github.com/headlamp-k8s/headlamp) | User-friendly Kubernetes UI — extensible with plugins | ![Stars](https://img.shields.io/github/stars/headlamp-k8s/headlamp?style=flat-square) |
| [vmware-tanzu/kubeapps](https://github.com/vmware-tanzu/kubeapps) | Web UI for deploying and managing apps in Kubernetes | ![Stars](https://img.shields.io/github/stars/vmware-tanzu/kubeapps?style=flat-square) |

---

## Cluster Management & CLI Tools

| Repository | Description | Stars |
|------------|-------------|-------|
| [ahmetb/kubectx](https://github.com/ahmetb/kubectx) | Switch between clusters and namespaces quickly | ![Stars](https://img.shields.io/github/stars/ahmetb/kubectx?style=flat-square) |
| [stern/stern](https://github.com/stern/stern) | Multi-pod and container log tailing for Kubernetes | ![Stars](https://img.shields.io/github/stars/stern/stern?style=flat-square) |
| [crossplane/crossplane](https://github.com/crossplane/crossplane) | Cloud infrastructure control plane using K8s API | ![Stars](https://img.shields.io/github/stars/crossplane/crossplane?style=flat-square) |
| [ahmetb/kubectl-aliases](https://github.com/ahmetb/kubectl-aliases) | Hundreds of kubectl aliases — productivity boost | ![Stars](https://img.shields.io/github/stars/ahmetb/kubectl-aliases?style=flat-square) |
| [kubecolor/kubecolor](https://github.com/kubecolor/kubecolor) | Colorize kubectl output for readability | ![Stars](https://img.shields.io/github/stars/kubecolor/kubecolor?style=flat-square) |
| [derailed/popeye](https://github.com/derailed/popeye) | Kubernetes cluster sanitizer — scan for misconfiguration issues | ![Stars](https://img.shields.io/github/stars/derailed/popeye?style=flat-square) |
| [kubernetes-sigs/krew](https://github.com/kubernetes-sigs/krew) | Plugin manager for kubectl — 200+ plugins | ![Stars](https://img.shields.io/github/stars/kubernetes-sigs/krew?style=flat-square) |
| [sbstp/kubie](https://github.com/sbstp/kubie) | More powerful alternative to kubectx — per shell contexts | ![Stars](https://img.shields.io/github/stars/sbstp/kubie?style=flat-square) |
| [FairwindsOps/nova](https://github.com/FairwindsOps/nova) | Find outdated or deprecated Helm chart versions | ![Stars](https://img.shields.io/github/stars/FairwindsOps/nova?style=flat-square) |
| [rancher/rancher](https://github.com/rancher/rancher) | Complete container management platform — multi-cluster K8s | ![Stars](https://img.shields.io/github/stars/rancher/rancher?style=flat-square) |
| [kubernetes/kops](https://github.com/kubernetes/kops) | Kubernetes Operations — production K8s on AWS, GCE | ![Stars](https://img.shields.io/github/stars/kubernetes/kops?style=flat-square) |
| [kubernetes-sigs/kubespray](https://github.com/kubernetes-sigs/kubespray) | Deploy production-ready Kubernetes with Ansible | ![Stars](https://img.shields.io/github/stars/kubernetes-sigs/kubespray?style=flat-square) |

---

## Service Mesh & Networking

| Repository | Description | Stars |
|------------|-------------|-------|
| [istio/istio](https://github.com/istio/istio) | Connect, secure, control, and observe microservices | ![Stars](https://img.shields.io/github/stars/istio/istio?style=flat-square) |
| [linkerd/linkerd2](https://github.com/linkerd/linkerd2) | Ultra-lightweight service mesh — zero-config mTLS | ![Stars](https://img.shields.io/github/stars/linkerd/linkerd2?style=flat-square) |
| [cilium/cilium](https://github.com/cilium/cilium) | eBPF-based networking, observability, security for K8s | ![Stars](https://img.shields.io/github/stars/cilium/cilium?style=flat-square) |
| [hashicorp/consul](https://github.com/hashicorp/consul) | HashiCorp Consul — service mesh + service discovery | ![Stars](https://img.shields.io/github/stars/hashicorp/consul?style=flat-square) |
| [kumahq/kuma](https://github.com/kumahq/kuma) | Universal service mesh — K8s and VMs | ![Stars](https://img.shields.io/github/stars/kumahq/kuma?style=flat-square) |
| [metallb/metallb](https://github.com/metallb/metallb) | Load balancer implementation for bare metal Kubernetes | ![Stars](https://img.shields.io/github/stars/metallb/metallb?style=flat-square) |
| [kubernetes/ingress-nginx](https://github.com/kubernetes/ingress-nginx) | NGINX Ingress Controller for Kubernetes | ![Stars](https://img.shields.io/github/stars/kubernetes/ingress-nginx?style=flat-square) |
| [traefik/traefik](https://github.com/traefik/traefik) | Traefik as Kubernetes Ingress Controller | ![Stars](https://img.shields.io/github/stars/traefik/traefik?style=flat-square) |
| [kubernetes-sigs/gateway-api](https://github.com/kubernetes-sigs/gateway-api) | Kubernetes Gateway API — next-gen ingress spec | ![Stars](https://img.shields.io/github/stars/kubernetes-sigs/gateway-api?style=flat-square) |

---

## Autoscaling & Resource Management

| Repository | Description | Stars |
|------------|-------------|-------|
| [kubernetes/autoscaler](https://github.com/kubernetes/autoscaler) | Cluster Autoscaler + Vertical Pod Autoscaler | ![Stars](https://img.shields.io/github/stars/kubernetes/autoscaler?style=flat-square) |
| [kedacore/keda](https://github.com/kedacore/keda) | Event-driven autoscaling for Kubernetes — 50+ scalers | ![Stars](https://img.shields.io/github/stars/kedacore/keda?style=flat-square) |
| [FairwindsOps/goldilocks](https://github.com/FairwindsOps/goldilocks) | Right-size your Kubernetes resource requests | ![Stars](https://img.shields.io/github/stars/FairwindsOps/goldilocks?style=flat-square) |
| [opencost/opencost](https://github.com/opencost/opencost) | Real-time cost monitoring for Kubernetes workloads | ![Stars](https://img.shields.io/github/stars/opencost/opencost?style=flat-square) |
| [robusta-dev/robusta](https://github.com/robusta-dev/robusta) | Kubernetes observability and automation platform | ![Stars](https://img.shields.io/github/stars/robusta-dev/robusta?style=flat-square) |

---

## Security & Policy

| Repository | Description | Stars |
|------------|-------------|-------|
| [aquasecurity/trivy](https://github.com/aquasecurity/trivy) | Comprehensive K8s security scanner — misconfigs, CVEs | ![Stars](https://img.shields.io/github/stars/aquasecurity/trivy?style=flat-square) |
| [aquasecurity/kube-bench](https://github.com/aquasecurity/kube-bench) | Check K8s cluster against CIS Kubernetes Benchmark | ![Stars](https://img.shields.io/github/stars/aquasecurity/kube-bench?style=flat-square) |
| [open-policy-agent/opa](https://github.com/open-policy-agent/opa) | General-purpose policy engine for K8s admission control | ![Stars](https://img.shields.io/github/stars/open-policy-agent/opa?style=flat-square) |
| [open-policy-agent/gatekeeper](https://github.com/open-policy-agent/gatekeeper) | OPA-based policy controller for Kubernetes | ![Stars](https://img.shields.io/github/stars/open-policy-agent/gatekeeper?style=flat-square) |
| [kyverno/kyverno](https://github.com/kyverno/kyverno) | Kubernetes-native policy management — no Rego needed | ![Stars](https://img.shields.io/github/stars/kyverno/kyverno?style=flat-square) |
| [falcosecurity/falco](https://github.com/falcosecurity/falco) | Runtime security for K8s — syscall-level threat detection | ![Stars](https://img.shields.io/github/stars/falcosecurity/falco?style=flat-square) |
| [bitnami-labs/sealed-secrets](https://github.com/bitnami-labs/sealed-secrets) | Encrypt K8s secrets — safe to store in Git | ![Stars](https://img.shields.io/github/stars/bitnami-labs/sealed-secrets?style=flat-square) |
| [external-secrets/external-secrets](https://github.com/external-secrets/external-secrets) | Sync secrets from AWS SM, Vault, GCP into K8s | ![Stars](https://img.shields.io/github/stars/external-secrets/external-secrets?style=flat-square) |

---

## Debugging & Troubleshooting

| Repository | Description | Stars |
|------------|-------------|-------|
| [zegl/kube-score](https://github.com/zegl/kube-score) | Static analysis of K8s manifests — security and reliability | ![Stars](https://img.shields.io/github/stars/zegl/kube-score?style=flat-square) |
| [robscott/kube-capacity](https://github.com/robscott/kube-capacity) | View resource requests, limits, and utilization | ![Stars](https://img.shields.io/github/stars/robscott/kube-capacity?style=flat-square) |
| [nicolaka/netshoot](https://github.com/nicolaka/netshoot) | Network troubleshooting toolkit for Docker and K8s | ![Stars](https://img.shields.io/github/stars/nicolaka/netshoot?style=flat-square) |
| [inspektor-gadget/inspektor-gadget](https://github.com/inspektor-gadget/inspektor-gadget) | eBPF-based tooling for debugging K8s apps | ![Stars](https://img.shields.io/github/stars/inspektor-gadget/inspektor-gadget?style=flat-square) |
| [ahmetb/kubectl-tree](https://github.com/ahmetb/kubectl-tree) | Show ownership hierarchy of K8s objects as a tree | ![Stars](https://img.shields.io/github/stars/ahmetb/kubectl-tree?style=flat-square) |
| [FairwindsOps/pluto](https://github.com/FairwindsOps/pluto) | Find deprecated Kubernetes API versions in code | ![Stars](https://img.shields.io/github/stars/FairwindsOps/pluto?style=flat-square) |

---

## Operators & Controllers

| Repository | Description | Stars |
|------------|-------------|-------|
| [operator-framework/operator-sdk](https://github.com/operator-framework/operator-sdk) | Build Kubernetes operators — Go, Ansible, Helm | ![Stars](https://img.shields.io/github/stars/operator-framework/operator-sdk?style=flat-square) |
| [kubernetes-sigs/kubebuilder](https://github.com/kubernetes-sigs/kubebuilder) | Framework for building K8s APIs — controller-runtime | ![Stars](https://img.shields.io/github/stars/kubernetes-sigs/kubebuilder?style=flat-square) |
| [kubernetes-sigs/controller-runtime](https://github.com/kubernetes-sigs/controller-runtime) | Libraries for building K8s controllers | ![Stars](https://img.shields.io/github/stars/kubernetes-sigs/controller-runtime?style=flat-square) |
| [metacontroller/metacontroller](https://github.com/metacontroller/metacontroller) | Write K8s controllers in any language | ![Stars](https://img.shields.io/github/stars/metacontroller/metacontroller?style=flat-square) |

---

## Serverless on Kubernetes

| Repository | Description | Stars |
|------------|-------------|-------|
| [knative/serving](https://github.com/knative/serving) | Serverless workloads on Kubernetes — auto-scales to zero | ![Stars](https://img.shields.io/github/stars/knative/serving?style=flat-square) |
| [openfaas/faas](https://github.com/openfaas/faas) | Serverless functions made simple on Kubernetes | ![Stars](https://img.shields.io/github/stars/openfaas/faas?style=flat-square) |
| [fission/fission](https://github.com/fission/fission) | Fast serverless functions for Kubernetes — millisecond cold start | ![Stars](https://img.shields.io/github/stars/fission/fission?style=flat-square) |

---

[← Back to Index](../README.md)
