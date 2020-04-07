name: Consul-OSS-Workshop
class: title
count: false
![:scale 30%](images/consul_logo.svg)
.titletext[
Consul OSS Workshop]
Connect and Secure Services across any platform.

???
Welcome to the beginner's guide to Consul OSS. This slide deck and accompanying labs can be presented as an instructor-led or self-guided workshop. If you're presenting this workshop be sure to read through all the speaker notes and the associated Instruqt tracks. This content is suitable for a 3-4 hour workshop.

---
name: Link-to-Slide-Deck
The Slide Deck
-------------------------
<br><br><br>
.center[
Follow along on your own computer at this link:

### [https://hashicorp.github.io/field-workshops-consul/slides/multi-cloud/consul-oss](https://hashicorp.github.io/field-workshops-consul/slides/multi-cloud/consul-oss)
]

???
These slides are published using the RemarkJS framework and Github Pages. View the source code for both the slide deck and the Instruqt labs here: https://www.github.com/hashicorp/field-workshops-consul. You may need to be invited to get access to this private code repo.

---
name: Introductions
Introductions
-------------------------

.contents[
* Your Name
* Job Title
* Automation Experience
]

???
Use this slide to introduce yourself, give a little bit of your background story, then go around the room and have all your participants introduce themselves.

---
name: Table-of-Contents
Table of Contents
=========================

1. Consul OSS to Consul Enterprise
1. Consul as a Service on AWS
1. Consul Enterprise - Platform
    * Lab 1a - Automated Upgrades & Autopilot
1. Consul Enterprise - Governance and Policy
    * Lab 1b - Namespaces
1. Consul Enterprise - Global Visibility, Routing and Scale
    * Lab 1c - Network Segments
1. Consul on Kubernetes
    * Lab 1d - Consul Helm

???
For today's session we are going to be covering the following topics.  
We are going to do an overview of why you even need consul.  Then we will go over how consul works from an architecture perspective.  We will then dive into some of the use cases that you would use consul for.  After that we will get our hands dirty with some labs starting with getting comfortable interacting with consul, then moving to service discovery and finally looking at consul connect and service segmentation.  Any questions?  Ok lets go!!
