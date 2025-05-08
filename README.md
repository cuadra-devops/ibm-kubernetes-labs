# ibm-kubernetes-labs# 🐳 IBM Kubernetes, Docker & OpenShift Certification Labs And Final Project.

Welcome to my lab portfolio! This repository documents my hands-on learning journey through the **IBM Skills Network Certification** for Kubernetes, Docker, and OpenShift. It includes summaries of each lab, what I learned, and key technologies used. 
--
\\## 🧠 Overview

- 🎓 **Certification**: IBM Introduction to Containers, Kubernetes, and OpenShift
- 📅 **Final Project**: – Guestbook Application Deployment
- ☁️ **Key Skills**: Kubernetes, Docker, OpenShift, CI/CD, Autoscaling, YAML, ConfigMaps, Secrets, Persistent Volumes
- 🔧 **Tools Used**: `kubectl`, `oc CLI`, IBM Cloud CLI, Docker, kubernetes.

## Completed Labs

### 1. [Lab:Introduction to Containers, Docker, and IBM Cloud Container Registry](https://www.coursera.org/learn/ibm-containers-docker-kubernetes-openshift/ungradedLti/kgtxc/lab-introduction-to-containers-docker-and-ibm-cloud-container-registry)

**What I Did:**
- Pulled an image from Docker Hub
- Ran containers using Docker CLI
- Built a Docker image using a Dockerfile
- Pushed the image to IBM Cloud Container Registry

### 2. [Lab:Practice Lab: Introduction to Kubernetes Objects](https://www.coursera.org/learn/ibm-containers-docker-kubernetes-openshift/ungradedLti/CFJWM/practice-lab-introduction-to-kubernetes-objects)  

**What I Did:**
- Created Kubernetes Services
- Deployed StatefulSets and DaemonSets
- Practiced `kubectl` commands and explored pod management

**Skills Gained:** Kubernetes objects, services, multi-node workloads

### 3. [Lab: Scaling and Updating Applications](https://www.coursera.org/learn/ibm-containers-docker-kubernetes-openshift/ungradedLti/SMHuo/hands-on-lab-scaling-and-updating-applications)
**What I Did:**
- Scaled applications with ReplicaSets
- Implemented rolling updates
- Managed app configuration with ConfigMaps
- Enabled Horizontal Pod Autoscaler
**Skills Gained:** CI/CD readiness, zero-downtime deployments, autoscaling

### 4. [Lab: Introduction to RedHat OpenShift](https://www.coursera.org/learn/ibm-containers-docker-kubernetes-openshift/ungradedLti/Hz976/lab-introduction-to-openshift)  
**What I Did:**
- Used the OpenShift CLI (`oc`) and Web Console
- Built applications using the Source-to-Image (s2i) strategy
- Inspected BuildConfig and ImageStreams
- Autoscaled deployed apps within OpenShift

**Skills Gained:** OpenShift CLI, automated image builds, autoscaling

### 5. [Practice Project - Understanding ConfigMaps, DaemonSets, Kubernetes Services, Secrets & Persistent Volume Claims](https://www.coursera.org/learn/ibm-containers-docker-kubernetes-openshift/ungradedLti/CiM7w/practice-project-understanding-configmaps-daemonsets-kubernetes-services-secrets)  
In this practice project I did the following: ConfigMap, DaemonSet, Kubernetes Service, Secret, andVolumes and Persistent Volume Claims.
1.how to set up a ConfigMap to manage configuration data for the myapp application.
2.create a DaemonSet to ensure that a pod runs on each node in the cluster, including the nodes where the 'myapp' pods are deployed.
3.create a Kubernetes Service to expose your application within the cluster.
4.create and manage secrets in Kubernetes to securely store sensitive information, such as passwords, tokens, and SSH keys.
5. how to define volumes and persistent volume claims (PVCs) in Kubernetes to provide storage for your application.

## 🚀 Final Project: Guestbook Application Deployment - [https://www.coursera.org/learn/ibm-containers-docker-kubernetes-openshift/ungradedLti/z3P8y/optional-deploy-guestbook-app-from-the-openshift-internal-registry]

**Project Summary**:
Deploying a cloud-native Guestbook app with full Kubernetes management.

**Planned Features:**
- Kubernetes Deployments for frontend/backend
- Horizontal Pod Autoscaling based on CPU metrics
- Rolling updates and rollback testing
- Use of ConfigMaps, Secrets, and Persistent Volumes
## Summary
This repository showcases my completed hands-on labs and final project for the IBM Kubernetes, Docker, and OpenShift certification, demonstrating practical skills in containerization, orchestration, and cloud-native DevOps.
