# Kubernetes Command Reference

Common `kubectl` commands practiced during Kubernetes hands-on labs.

## Cluster Management

List all nodes in the Kubernetes cluster.

```bash
kubectl get nodes
```

## Pod Management

### Create a Pod

Create a Pod using a YAML manifest.

```bash
kubectl create -f nginx-pod.yaml
```

### List Pods

Display Pods in the current namespace.

```bash
kubectl get pods
```

### Inspect Pods

Show detailed information about Pods.

```bash
kubectl describe pods
```

### List Pods with Additional Details

Display Pod IP addresses and assigned nodes.

```bash
kubectl get pods -o wide
```

### Get a Specific Pod

```bash
kubectl get pod nginx-pod
```

### List Pods Across All Namespaces

```bash
kubectl get pods --all-namespaces
```

### Delete a Pod

```bash
kubectl delete pod nginx-pod
```

## Notes

- `kubectl get` lists Kubernetes resources.
- `kubectl describe` displays detailed resource information and events.
- `kubectl create -f` creates resources from a manifest.
- `kubectl apply -f` creates or updates resources declaratively.
- `kubectl delete` removes Kubernetes resources.
- `-o wide` displays additional information.
- `--all-namespaces` lists resources across every namespace.
