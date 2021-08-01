DnH DevOps Study Group
---

### Goal: 

Have an understanding of the role of DevOps, Site Reliability Engineering and related concepts in the world of software engineering.

### Idea:

A lot of us know how software is written, but few of us have an opportunity to understand how it is built, deployed and operated. Let us peek under the covers and learn about how Operating Systems, Cloud services, Continuous Integration/Continuous Delivery and Cloud Native software together come together as a platform for our software. While learning about this, we'll also explore how to make this platform more reliable and scaleable.

### Outline

* The basics - OS
  * Linux - Desktop v/s Server distros - CLI isn't scary!
  * Filesystem Hierarchy Standard - know your way around the disk
  * Basics of working with Shell - edit files, change permissions, change directories,  handle files, etc (can skip this part if participants are familiar)
  * `sudo` and not shooting yourself in the foot - when to use it (pretty much always), `visudo`, and how you might end up changing perms on files/directories used by services
  * `init`-like systems and `systemd`
  * Any other bits from The Missing Semester that might be relevant, based on feedback from participants
  * A bit about package management - what does it do? common gotchas (security upgrades can also break functionality!) with updating packages. apt vs yum vs homebrew
* The basics - Cloud
  * VPS vs Cloud
    * Virtual Machines
      * EC2, ECS - Compute + Storage
      * VPC - Network
      * IAM - Security/Authorisations
    * Managed Services - S3, SQS
    * Serverless
  * IaaS/PaaS
    * Heroku, Glitch
  * Cloud/VPS Providers
    * AWS/GCP/Azure/DO/Vultr/Scaleway/Linode
* The basics - Provisioning tools
  * Infrastructure Provisioning
    * Terraform/CDK/CloudFormation
  * Software Provisioning/Config Management
    * Ansible/Puppet/Chef/Salt
* CI/CD
  * Demystifying CI/CD
  * Why do we build?
    * Do interpreted languages need a build pipeline too?
    * How to get a clean room build every time?
  * Jenkins - the elephant in the room. Other tools in this space!
  * Every pipeline is custom to that team/company!
  * All Tests Matter :tm:
  * Make lots of small changes, make it easy to roll them back!
* The basics - Cloud Native
  * Docker
    * Containers vs VMs
    * Images, Layers, Containers
  * Orchestration
    * Why
  * Orchestrators in the Market
    * Swarm, Kubernetes, Nomad
  * Service Discovery?
  * Secrets Management?
  * 12 Factor App
* Advanced - Cloud Native
  * Docker + Python - https://github.com/Apress/practical-docker-with-python
  * Kubernetes in Docker/k3s
  * Kube the hard way - https://github.com/kelseyhightower/kubernetes-the-hard-way
* Advanced - Distributed systems and Architecture
  * Walk through https://github.com/donnemartin/system-design-primer maybe?

### Method: 

We start with some lectures from the [Missing Semester](https://www.youtube.com/playlist?list=PLyzOVJj3bHQuloKGG59rS43e29ro7I57J) sessions, and then work through the outline below. During each session, we'll cover questions about the topics we learnt in the past week, spend some time discussing the basic concepts for next week and share some self learning content for the next week.

We will also have a text channel where we can post questions or doubts throughout the week so that we can discuss asynchronously and everyone can watch the lectures at their own pace. The expectation is that people are regular for the meetings and interested in learning more about databases. 

### Schedule: 

Tentative cadence: 2 weeks of calls, 1 week break, rinse and repeat.

- August 1        : Introductory call and gauge interest in topics from people
- August 1 - 8    : Watch Lecture 1 and 2 of Missing Semester
- August 8        : 30 mins meeting to discuss last week's learnings. 
- so on...


