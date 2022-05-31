---
layout: details
filename: chef
name: Chef
image: /tech-radar/assets/images/platforms/chef.png 
category: Platforms
ring: Drop
---

# What is it ?
Chef is an automation tool that provides a way to define infrastructure as code (IAC). Chef uses a pure-Ruby, domain-specific language (DSL) for writing system configurations. 

# Why ?
Chef has been used at Administrate for about 10 years, first in https://github.com/Administrate/chef which is not archived and then https://github.com/Administrate/cuisinier. Chef is being used to automate the provisioning of bare metal EC2 servers by installing the declared libraries, and also ship updated code by pulling the latest commits from a specific branch in a git repository.

As services are being moved to use Docker to encapsulate the dependencies and code to run, chef is no longer required as a provisioning tool. 

# Resources
- [Homepage](https://www.chef.io/)
