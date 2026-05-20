# DevOps — Docker & Containers

> Comprehensive collection of Docker tools, container runtimes, image building, security, orchestration, networking, and container management.

---

## Core Container Runtime & Engine

| Repository | Description | Stars |
|------------|-------------|-------|
| [moby/moby](https://github.com/moby/moby) | Moby — the open source container engine powering Docker | ![Stars](https://img.shields.io/github/stars/moby/moby?style=flat-square) |
| [docker/cli](https://github.com/docker/cli) | The official Docker CLI | ![Stars](https://img.shields.io/github/stars/docker/cli?style=flat-square) |
| [containerd/containerd](https://github.com/containerd/containerd) | Industry-standard container runtime — CNCF graduated | ![Stars](https://img.shields.io/github/stars/containerd/containerd?style=flat-square) |
| [opencontainers/runc](https://github.com/opencontainers/runc) | CLI tool for spawning containers — OCI spec reference impl | ![Stars](https://img.shields.io/github/stars/opencontainers/runc?style=flat-square) |
| [containers/podman](https://github.com/containers/podman) | Daemonless container engine — Docker alternative, rootless | ![Stars](https://img.shields.io/github/stars/containers/podman?style=flat-square) |
| [lima-vm/lima](https://github.com/lima-vm/lima) | Linux VMs on macOS — Docker Desktop alternative | ![Stars](https://img.shields.io/github/stars/lima-vm/lima?style=flat-square) |
| [containerd/nerdctl](https://github.com/containerd/nerdctl) | Docker-compatible CLI for containerd — supports Compose | ![Stars](https://img.shields.io/github/stars/containerd/nerdctl?style=flat-square) |
| [rootless-containers/rootlesskit](https://github.com/rootless-containers/rootlesskit) | Linux-native fake root for rootless containers | ![Stars](https://img.shields.io/github/stars/rootless-containers/rootlesskit?style=flat-square) |

---

## Docker Compose & Multi-Container

| Repository | Description | Stars |
|------------|-------------|-------|
| [docker/compose](https://github.com/docker/compose) | Define and run multi-container Docker applications | ![Stars](https://img.shields.io/github/stars/docker/compose?style=flat-square) |
| [louislam/dockge](https://github.com/louislam/dockge) | Fancy docker-compose.yaml stack manager with UI | ![Stars](https://img.shields.io/github/stars/louislam/dockge?style=flat-square) |
| [nicolo-ribaudo/compose-spec](https://github.com/compose-spec/compose-spec) | The Compose Specification — multi-container apps standard | ![Stars](https://img.shields.io/github/stars/compose-spec/compose-spec?style=flat-square) |
| [ctop](https://github.com/bcicen/ctop) | Top-like interface for container metrics | ![Stars](https://img.shields.io/github/stars/bcicen/ctop?style=flat-square) |
| [nicolo-ribaudo/kompose](https://github.com/kubernetes/kompose) | Convert Docker Compose files to Kubernetes manifests | ![Stars](https://img.shields.io/github/stars/kubernetes/kompose?style=flat-square) |

---

## Image Building & Optimization

| Repository | Description | Stars |
|------------|-------------|-------|
| [moby/buildkit](https://github.com/moby/buildkit) | Next-gen Docker image builder — concurrent, cache-efficient | ![Stars](https://img.shields.io/github/stars/moby/buildkit?style=flat-square) |
| [GoogleContainerTools/kaniko](https://github.com/GoogleContainerTools/kaniko) | Build container images inside Kubernetes — no Docker daemon | ![Stars](https://img.shields.io/github/stars/GoogleContainerTools/kaniko?style=flat-square) |
| [GoogleContainerTools/distroless](https://github.com/GoogleContainerTools/distroless) | Minimal language-focused Docker base images — no shell, no bloat | ![Stars](https://img.shields.io/github/stars/GoogleContainerTools/distroless?style=flat-square) |
| [wagoodman/dive](https://github.com/wagoodman/dive) | Explore Docker image layers — find ways to shrink image size | ![Stars](https://img.shields.io/github/stars/wagoodman/dive?style=flat-square) |
| [docker-slim/docker-slim](https://github.com/slimtoolkit/slim) | Slim your Docker images — up to 30x smaller | ![Stars](https://img.shields.io/github/stars/slimtoolkit/slim?style=flat-square) |
| [nicolo-ribaudo/buildpacks](https://github.com/buildpacks/pack) | Build apps using Cloud Native Buildpacks — no Dockerfile | ![Stars](https://img.shields.io/github/stars/buildpacks/pack?style=flat-square) |
| [nicolo-ribaudo/ko](https://github.com/ko-build/ko) | Build and deploy Go containers — no Dockerfile needed | ![Stars](https://img.shields.io/github/stars/ko-build/ko?style=flat-square) |
| [nicolo-ribaudo/jib](https://github.com/GoogleContainerTools/jib) | Build Java container images without Docker — Maven/Gradle plugin | ![Stars](https://img.shields.io/github/stars/GoogleContainerTools/jib?style=flat-square) |
| [nicolo-ribaudo/img](https://github.com/genuinetools/img) | Standalone, daemon-less, unprivileged Docker image builder | ![Stars](https://img.shields.io/github/stars/genuinetools/img?style=flat-square) |

---

## Container Security

| Repository | Description | Stars |
|------------|-------------|-------|
| [aquasecurity/trivy](https://github.com/aquasecurity/trivy) | All-in-one security scanner — images, repos, configs, IaC | ![Stars](https://img.shields.io/github/stars/aquasecurity/trivy?style=flat-square) |
| [hadolint/hadolint](https://github.com/hadolint/hadolint) | Dockerfile linter — validates best practices and shell scripts | ![Stars](https://img.shields.io/github/stars/hadolint/hadolint?style=flat-square) |
| [falcosecurity/falco](https://github.com/falcosecurity/falco) | Runtime security — detects threats using syscall monitoring | ![Stars](https://img.shields.io/github/stars/falcosecurity/falco?style=flat-square) |
| [anchore/grype](https://github.com/anchore/grype) | Vulnerability scanner for container images and filesystems | ![Stars](https://img.shields.io/github/stars/anchore/grype?style=flat-square) |
| [anchore/syft](https://github.com/anchore/syft) | CLI tool for generating SBOM from container images | ![Stars](https://img.shields.io/github/stars/anchore/syft?style=flat-square) |
| [containers/skopeo](https://github.com/containers/skopeo) | Work with container images and registries — inspect, copy, sign | ![Stars](https://img.shields.io/github/stars/containers/skopeo?style=flat-square) |
| [open-policy-agent/opa](https://github.com/open-policy-agent/opa) | General-purpose policy engine — enforce container policies | ![Stars](https://img.shields.io/github/stars/open-policy-agent/opa?style=flat-square) |
| [aquasecurity/kube-bench](https://github.com/aquasecurity/kube-bench) | Check Kubernetes deployment against CIS benchmarks | ![Stars](https://img.shields.io/github/stars/aquasecurity/kube-bench?style=flat-square) |
| [deepfence/ThreatMapper](https://github.com/deepfence/ThreatMapper) | Open source cloud native security observability platform | ![Stars](https://img.shields.io/github/stars/deepfence/ThreatMapper?style=flat-square) |

---

## Container Management UIs

| Repository | Description | Stars |
|------------|-------------|-------|
| [portainer/portainer](https://github.com/portainer/portainer) | Docker and K8s management UI — most popular container UI | ![Stars](https://img.shields.io/github/stars/portainer/portainer?style=flat-square) |
| [jesseduffield/lazydocker](https://github.com/jesseduffield/lazydocker) | Terminal UI for Docker — manage containers from CLI | ![Stars](https://img.shields.io/github/stars/jesseduffield/lazydocker?style=flat-square) |
| [nicolo-ribaudo/yacht](https://github.com/SelfhostedPro/Yacht) | Container management UI — focused on templates | ![Stars](https://img.shields.io/github/stars/SelfhostedPro/Yacht?style=flat-square) |
| [nicolo-ribaudo/dockerwatch](https://github.com/francescou/docker-compose-ui) | Web UI for Docker Compose | ![Stars](https://img.shields.io/github/stars/francescou/docker-compose-ui?style=flat-square) |
| [bcicen/ctop](https://github.com/bcicen/ctop) | Top-like interface for container metrics in terminal | ![Stars](https://img.shields.io/github/stars/bcicen/ctop?style=flat-square) |
| [nicolo-ribaudo/oxker](https://github.com/mrjackwills/oxker) | Simple TUI to display and control Docker containers | ![Stars](https://img.shields.io/github/stars/mrjackwills/oxker?style=flat-square) |

---

## Container Registries

| Repository | Description | Stars |
|------------|-------------|-------|
| [goharbor/harbor](https://github.com/goharbor/harbor) | Open source trusted cloud native registry — CNCF graduated | ![Stars](https://img.shields.io/github/stars/goharbor/harbor?style=flat-square) |
| [distribution/distribution](https://github.com/distribution/distribution) | Docker Registry 2.0 reference implementation | ![Stars](https://img.shields.io/github/stars/distribution/distribution?style=flat-square) |
| [project-zot/zot](https://github.com/project-zot/zot) | OCI-native container registry — lightweight, CNCF | ![Stars](https://img.shields.io/github/stars/project-zot/zot?style=flat-square) |
| [google/go-containerregistry](https://github.com/google/go-containerregistry) | Go library and CLI tools for working with container registries | ![Stars](https://img.shields.io/github/stars/google/go-containerregistry?style=flat-square) |
| [nicolo-ribaudo/crane](https://github.com/google/go-containerregistry) | Crane — tool for interacting with remote images and registries | ![Stars](https://img.shields.io/github/stars/google/go-containerregistry?style=flat-square) |
| [nicolo-ribaudo/regclient](https://github.com/regclient/regclient) | Docker and OCI registry client — copy, tag, inspect | ![Stars](https://img.shields.io/github/stars/regclient/regclient?style=flat-square) |

---

## Container Networking

| Repository | Description | Stars |
|------------|-------------|-------|
| [cilium/cilium](https://github.com/cilium/cilium) | eBPF-based networking, security, and observability for containers | ![Stars](https://img.shields.io/github/stars/cilium/cilium?style=flat-square) |
| [flannel-io/flannel](https://github.com/flannel-io/flannel) | Simple overlay network for containers — used by K3s | ![Stars](https://img.shields.io/github/stars/flannel-io/flannel?style=flat-square) |
| [nicolo-ribaudo/weave](https://github.com/weaveworks/weave) | Simple, resilient multi-host Docker networking | ![Stars](https://img.shields.io/github/stars/weaveworks/weave?style=flat-square) |
| [nicolo-ribaudo/netshoot](https://github.com/nicolaka/netshoot) | Docker and Kubernetes network troubleshooting toolkit | ![Stars](https://img.shields.io/github/stars/nicolaka/netshoot?style=flat-square) |
| [nicolo-ribaudo/traefik](https://github.com/traefik/traefik) | Cloud native proxy — auto-discovers Docker containers | ![Stars](https://img.shields.io/github/stars/traefik/traefik?style=flat-square) |
| [nicolo-ribaudo/caddy-docker-proxy](https://github.com/lucaslorentz/caddy-docker-proxy) | Caddy as a reverse proxy for Docker containers | ![Stars](https://img.shields.io/github/stars/lucaslorentz/caddy-docker-proxy?style=flat-square) |

---

## Container Storage & Volumes

| Repository | Description | Stars |
|------------|-------------|-------|
| [rook/rook](https://github.com/rook/rook) | Cloud-native storage orchestrator for Kubernetes — Ceph | ![Stars](https://img.shields.io/github/stars/rook/rook?style=flat-square) |
| [longhorn/longhorn](https://github.com/longhorn/longhorn) | Distributed block storage for Kubernetes — CNCF | ![Stars](https://img.shields.io/github/stars/longhorn/longhorn?style=flat-square) |
| [openebs/openebs](https://github.com/openebs/openebs) | Container attached storage — Kubernetes native | ![Stars](https://img.shields.io/github/stars/openebs/openebs?style=flat-square) |
| [nicolo-ribaudo/local-path-provisioner](https://github.com/rancher/local-path-provisioner) | Rancher's dynamic local path provisioner for K8s | ![Stars](https://img.shields.io/github/stars/rancher/local-path-provisioner?style=flat-square) |

---

## Docker Developer Tools & Utilities

| Repository | Description | Stars |
|------------|-------------|-------|
| [nicolo-ribaudo/docker-bench-security](https://github.com/docker/docker-bench-security) | Script checking Docker host vs CIS Docker Benchmark | ![Stars](https://img.shields.io/github/stars/docker/docker-bench-security?style=flat-square) |
| [nicolo-ribaudo/lazydocker](https://github.com/jesseduffield/lazydocker) | Terminal UI for Docker and docker-compose | ![Stars](https://img.shields.io/github/stars/jesseduffield/lazydocker?style=flat-square) |
| [nicolo-ribaudo/docuum](https://github.com/stepchowfun/docuum) | Least recently used Docker image eviction | ![Stars](https://img.shields.io/github/stars/stepchowfun/docuum?style=flat-square) |
| [nicolo-ribaudo/dockly](https://github.com/lirantal/dockly) | Immersive terminal interface for Docker | ![Stars](https://img.shields.io/github/stars/lirantal/dockly?style=flat-square) |
| [nicolo-ribaudo/docker-osx](https://github.com/sickcodes/Docker-OSX) | Run macOS in Docker — near-native performance | ![Stars](https://img.shields.io/github/stars/sickcodes/Docker-OSX?style=flat-square) |
| [nicolo-ribaudo/dockerize](https://github.com/jwilder/dockerize) | Utility to simplify running apps in Docker containers | ![Stars](https://img.shields.io/github/stars/jwilder/dockerize?style=flat-square) |

---

## Awesome Docker Curated Lists

| Repository | Description | Stars |
|------------|-------------|-------|
| [veggiemonk/awesome-docker](https://github.com/veggiemonk/awesome-docker) | Curated list of Docker resources and projects — comprehensive | ![Stars](https://img.shields.io/github/stars/veggiemonk/awesome-docker?style=flat-square) |
| [nicolo-ribaudo/dockersamples](https://github.com/dockersamples) | Official Docker sample applications | ![Stars](https://img.shields.io/github/stars/dockersamples/example-voting-app?style=flat-square) |

---

[← Back to Index](../README.md)
