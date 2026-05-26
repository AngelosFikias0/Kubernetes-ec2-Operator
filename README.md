# ec2-operator

A Kubernetes operator built with Go and Kubebuilder that manages AWS EC2 instances as native Kubernetes custom resources.

## Overview

Extends Kubernetes to provision, manage, and terminate EC2 instances via CRDs.
Implements the full operator pattern: Reconcile Loop, Finalizers, Idempotency, and Informer/Cache internals.

## Stack

- Go
- Kubebuilder / controller-runtime
- AWS SDK for Go v2
- Helm
- K3D (local dev)

## Concepts Covered

- Custom Resource Definitions (CRDs)
- Reconcile loop (happy path, sad path, error handling)
- Finalizers and deletion lifecycle
- Informers, caches, and work queues
- RBAC and service accounts
- Helm packaging and deployment

## References

- [freeCodeCamp — Build Your Own Kubernetes Operators](https://www.youtube.com/watch?v=odP153inZUo)
- [Kubebuilder Book](https://book.kubebuilder.io)
