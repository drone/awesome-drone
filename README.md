# Awesome Drone [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curates list of awesome Drone resources.

## Table of Contents

- [Resources](#resources)
  - [Documentation](#documentation)
  - [Articles](#articles)
  - [Tutorials](#tutorials)
- [Libraries](#libraries)
- [Plugins](#plugins)
- [Secrets](#secrets)
- [Tools](#tools)
  - [Installation](#installation)

## Resources

### Documentation

* [go-training/drone-tutorial](https://github.com/go-training/drone-tutorial) - Drone Continuous Delivery Installation guide

### Articles

* [CI/CD tools comparison](https://www.digitalocean.com/community/tutorials/ci-cd-tools-comparison-jenkins-gitlab-ci-buildbot-drone-and-concourse) - by Digital Ocean

### Tutorials

* [gesellix/drone-stack](https://github.com/gesellix/drone-stack) - example Docker Stack using Swarm mode
* [appleboy/drone-on-kubernetes](https://github.com/appleboy/drone-on-kubernetes/) - Examples of how to run Drone on Kubernetes (AWS && GKE)
* [dellintosh/pipeline](https://github.com/dellintosh/pipeline) - Example end-to-end deployment pipeline using multiple Kubernetes clusters
* [Kubernetes on arm64](https://thepracticalsysadmin.com/set-up-drone-on-arm64-kubernetes-clusters/) - Tutorial for setting up Drone 1.0 on Kubernetes arm64 clusters

## Libraries

* [drone/drone-go](https://github.com/drone/drone-go) - official Go client
* [drone/drone.js](https://github.com/drone/drone-js) - official JavaScript client

## Plugins

* [mavimo/drone-chromewebstore](https://github.com/mavimo/drone-chromewebstore) - allow to upload and publish application on Chrome Webstore

## Secrets

* [drone/drone-secret-plugin-starter](https://github.com/drone/drone-secret-plugin-starter) - starter project for building your own secrets plugin
* [drone/drone-amazon-secrets](https://github.com/drone/drone-amazon-secrets) - plugin to source secrets from the AWS Secrets Manager 
* [drone/drone-vault](https://github.com/drone/drone-vault) - plugin to source secrets from Vault

## Tools

### Installation

* [Helm Chart](https://github.com/kubernetes/charts/tree/master/stable/drone) - official Helm Chart in [kubernetes/helm](https://github.com/kubernetes/charts)
* [yum repo](https://copr.fedorainfracloud.org/coprs/carlwgeorge/drone/) - RPM packages for installing drone-server, drone-agent, and drone-cli on Fedora, CentOS, and RHEL

### Infrastructure

* [Drone EC2 Supervisor](https://github.com/fountainheadtechnologies/drone-ec2-supervisor#drone-ec2-supervisor) - Automatically starts/stops an EC2 Instance based queued builds.
