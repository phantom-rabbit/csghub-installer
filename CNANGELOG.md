# Changelog

## v1.4.2 (To be released)

---

- [helm] Optimize password length
- [helm] Fixed the adaptation error when using external resources
    - Now support (postgres, redis, registry, object storage, gitaly)

## v1.4.1

---

- [all] Rollback configuration user email login through unified configuration
- [helm] Disabled tag resolving for knative serving for insecure registry by default
- [compose] Fixed permission issues when mapping volumes
- [compose] Allow users to turn off multi-source synchronization through simple configuration
- [compose] Allow users define data location
- [helm] Allow using external ingress-nginx
- [helm] Optimize the gitlab shell host key pair generation method
- [helm] Optimize automatic labeling behavior under automatic configuration for GPU resources

## v1.4.0

---

- [helm] Add knative serving and argo automatic configuration
- [helm] Optimize the number of ingresses
- [all] Add dataset preview component dataviewer
- [docker] Add docker quick configuration script quick_install.sh
- [docker] k8s integration is disabled by default 

