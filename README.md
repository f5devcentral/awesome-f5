<p align="center">
<a href="https://github.com/f5devcentral/awesome-f5"><img src="https://img.shields.io/badge/-awesome-red?style=flat&logo=f5&label=~+of" alt="awesome-f5"/></a>
<a href="https://github.com/f5devcentral/awesome-f5/activity"><img src="https://img.shields.io/github/contributors/f5devcentral/awesome-f5" alt="Contributors"/></a>
<a href="https://github.com/f5devcentral/awesome-f5/stargazers"><img src="https://img.shields.io/github/stars/f5devcentral/awesome-f5?color=red" alt="Stars"/></a>
</br>
<em>An <a href="awesome.md">awesome</a> list of tools that will help you with your F5 products</em>
</p>

---

Help make this list more awesome and [contribute](contributing.md)!

## Contents

- [Contents](#contents)
- [Ansible](#ansible)
- [Automation Toolchain](#automation-toolchain)
- [DevOps / CICD](#devops--cicd)
- [Distributed Cloud](#distributed-cloud)
- [iHealth](#ihealth)
- [Terraform](#terraform)
- [Ops tools](#ops-tools)
- [Video](#video)
- [VS Code](#vs-code)
- [Related](#related)

## Ansible

- [Tips and Tricks](https://community.f5.com/t5/technical-articles/f5-automation-with-ansible-tips-and-tricks/ta-p/290998) - This article links several videos that demonstrate step by step how to implement automation with Ansible.
- [Manage Infrastructure and Services Lifecycle with Terraform and Ansible](https://community.f5.com/t5/technical-articles/manage-infrastructure-and-services-lifecycle-with-terraform-and/ta-p/291358) - Overview and demo putting all the pieces of infrastructure and configuration automation.

## Automation Toolchain

- [Manage Infrastructure and Services Lifecycle with Terraform and Ansible](https://community.f5.com/t5/technical-articles/manage-infrastructure-and-services-lifecycle-with-terraform-and/ta-p/291358) - Overview and demo putting all the pieces of infrastructure and configuration automation.
- [JOURNEYS](https://github.com/f5devcentral/f5-journeys) - JOURNEYS is an application designed to assist F5 Customers with migrating a BIG-IP configuration to a new F5 device and enable new ways of migrating.
- [F5 BIG-IP Automation Config Converter](https://github.com/f5devcentral/f5-automation-config-converter) - F5 BIG-IP Automation Config Converter (BIG-IP ACC) is an app written in Node.js that converts a BIG-IP configuration into an AS3 declaration, distributed as an easy-to-use docker image.
- [tmconfjs](https://github.com/simonkowallik/tmconfjs) - Converts a BIG-IP configuration file (eg. bigip.conf) to JSON using the F5 BIG-IP Automation Config Converter parser. Written in javascript and available as a simple to use docker container image.

## DevOps / CICD

- [TesTcl](https://github.com/landro/TesTcl) - TesTcl is a Tcl library for unit testing iRules which are used when configuring F5 BIG-IP devices.
- [irulescan](https://github.com/simonkowallik/irulescan) - Static security analyzer for iRules (and your CI/CD pipelines) also [available as a GitHub Action](https://github.com/marketplace/actions/irules-security-scan).
- [tcl-smock](https://github.com/simonkowallik/tcl-smock) - A simple TCL mock implementation primarily designed for unit testing of F5 iApps and tmsh scripts.

## Distributed Cloud

- [xc-app-services-tf](https://github.com/Mikej81/xc-app-services-tf) - Mike Coleman examples of deploying app services in F5 XC with Terraform
- [Kubernetes architecture options with F5 XC](https://community.f5.com/t5/technical-articles/kubernetes-architecture-options-with-f5-distributed-cloud/ta-p/306550) - This article explores four major architectures in ascending order of sophistication and advantages

## iHealth

- [iHAC](https://github.com/simonkowallik/iHAC) - iHAC aims to be a simple and easy to use interface to a subset of features provided by F5 iHealth.

## Terraform

- [xc-app-services-tf](https://github.com/Mikej81/xc-app-services-tf) - Mike Coleman examples of deploying app services in F5 XC with Terraform
- [Manage Infrastructure and Services Lifecycle with Terraform and Ansible](https://community.f5.com/t5/technical-articles/manage-infrastructure-and-services-lifecycle-with-terraform-and/ta-p/291358) - Overview and demo putting all the pieces of infrastructure and configuration automation.

## Ops tools

- [f5-demo-httpd](https://github.com/f5devcentral/f5-demo-httpd) - Simple NGINX Demo App in a Container useful for testing
- [httpbin](https://github.com/simonkowallik/httpbin) - Ever heard of httpbin.org? This is a containerized and improved version of httpbin with added features running on nginx, unit, httpd or gunicorn!
- [f5-demo-radius](https://github.com/simonkowallik/docker/tree/master/f5-demo-radius) - Need to test authentication against Radius but don't want to setup freeRADIUS? This is a pre-configured container ready to authenticate your BIG-IP Admins!
- [tacacs_server](https://github.com/f5-rahm/tacacs_server) - Need to test authentication against TACACS but don't want to setup it up yourself? This is a Docker image/container setup for testing tacacs+ with F5 BIG-IP.

## Video

- [Mark Dittmer's YouTube Channel](https://www.youtube.com/@MarkDittmer/videos) - Kubernetes Ingress and Automation of BIG-IP

## VS Code

- [The F5 Extension](https://marketplace.visualstudio.com/items?itemName=F5DevCentral.vscode-f5) - This extension supercharges your abilities to work with the automation toolchain, iRules, and direct connects to BIG-IP devices.
- [F5 Networks iRules](https://marketplace.visualstudio.com/items?itemName=bitwisecook.irule) - This extension supports syntax and intelliSense support for iRule events, commands and statements, up to BIG-IP v17.1.
- [vscode-iApp](https://marketplace.visualstudio.com/items?itemName=bitwisecook.irule) [on GitHub](https://github.com/bitwisecook/vscode-iApp) - iApp extension for Visual Studio Code. This extension gives Tcl based iApp language support for Visual Studio Code including syntax and intelliSense support for iApp events, commands and statements.
- [vscode-f5-fast](https://github.com/f5devcentral/vscode-f5-fast) - F5 vscode extension dedicated to F5 FAST template authoring and deployment.

## Related

- [All Awesome Lists](https://github.com/topics/awesome) - All the Awesome lists on GitHub.
- [Awesome Search](https://awesomelists.top) - Quick search for Awesome lists.
- [StumbleUponAwesome](https://github.com/basharovV/StumbleUponAwesome) - Discover random pages from the Awesome dataset using a browser extension.
- [Awesome CLI](https://github.com/umutphp/awesome-cli) - A simple command-line tool to dive into Awesome lists.
- [Awesome Viewer](https://awesome.digitalbunker.dev) - A visualizer for all of the above Awesome lists.
- [Track Awesome List](https://www.trackawesomelist.com) - View the latest updates of Awesome lists.
