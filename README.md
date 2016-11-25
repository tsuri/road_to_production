# How to setup a kubernetes cluster

Gentle Reader,

  before starting this journey, please spend some time contemplating whether it is what you need.
What we will accomplish through great pain is not going to be substantially different from what Google, Amazon and other cloud providers offer you essentially out of the box.

Here I cronicle all the steps I went through while learning how to deploy Kubernetes on bare metal. The learning part is done on virtualbox VMs.

This is the plan, as of now:

Chapter 1, the underlying infrastructure. Here we will deploy a coreos cluster and we'll get familiar with some of the features.

Chapter 2, the base kubernetes cluster. We setup a very simple kubernetes cluster, using only unauthenticated HTTP for communication.

Chapter 3, we augment the base cluster with a few addons. In particular, we'll add a service domain name server. We would add more basic extensions here (in particular monitoring and a registry for container images) but many things are easier with authentication in place.

Chapter 4, authentication.

Chapter 5, monitoring

Chapter 6, container image registry

Chapter 7, authorization

Chapter 8, applications