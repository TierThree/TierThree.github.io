---
layout: post
title: "Automated Kubeadm Cluster"
date: 2022-05-11 
description: Automation of a Kubernetes Cluster build through Kubeadm
img: 
---

A lot of times I find myself automating tasks that are not often repeated, but find myself learning a lot from those tasks. One such thing is building a Kubernetes cluster in my own homelab. I have no real reason to automate this, I won't be doing it maybe more than once a year, but I'd still like to have an idea of how I may go about doing it.

That's why I created [this](https://github.com/TierThree/kubeadm-ansible-install)! These are three easy to use roles in order to pick up and establish a Kubeadm cluster. Feel free to pull this repo down and play with it yourself. I never truly made a main.yml to govern these, I imported the roles as needed where I needed during testing. The roles will perform a kubeadm installation, a main-node setup, and will join to a certain node as well!

I'll update this page as I make more changes and make it more dynamic!