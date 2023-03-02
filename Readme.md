# Mutate-Me

This is a mutation admission controller for kubernetes. 

## The Dev environment

Use this to build a [kind](https://kind.sigs.k8s.io/docs/user/quick-start/) environment for your local testing.

```
➜  mutate-me git:(master) ✗ kind create cluster --name dev-cluster --image kindest/node:v1.23.13

Creating cluster "dev-cluster" ...
 ✓ Ensuring node image (kindest/node:v1.23.13) 🖼 
 ✓ Preparing nodes 📦  
 ✓ Writing configuration 📜 
 ✓ Starting control-plane 🕹️ 
 ✓ Installing CNI 🔌 
 ✓ Installing StorageClass 💾 
Set kubectl context to "kind-dev-cluster"
You can now use your cluster with:

kubectl cluster-info --context kind-dev-cluster

Have a nice day! 👋
```

## About Go Packages 
- Gorilla MUX
- k8s.io/client-go

## How to get it

To get the latest version, use go1.16+ and fetch using the go get command. For example:

`go get k8s.io/client-go@latest`

To get a specific version, use go1.11+ and fetch the desired version using the go get command. For example:

`go get k8s.io/client-go@v0.20.4`

#supports v1.23 of k8s
