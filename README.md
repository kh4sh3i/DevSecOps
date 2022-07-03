<h1 align="center">
  <br>
  <a href=""><img src="https://1ohvy81v7br01wtgnj4bf0ek-wpengine.netdna-ssl.com/wp-content/uploads/2019/03/DevSecOps-Diagram.png" alt="" width="500px;"></a>
  <br>
  <img src="https://img.shields.io/badge/PRs-welcome-blue">
  <img src="https://img.shields.io/github/last-commit/kh4sh3i/DevSecOps">
  <img src="https://api.codacy.com/project/badge/Grade/e5fd334a431848dcb6ecdb3784fb5dfb">
  <a href="https://twitter.com/intent/follow?screen_name=kh4sh3i_"><img src="https://img.shields.io/twitter/follow/kh4sh3i_?style=flat&logo=twitter"></a>
  <a href="https://github.com/kh4sh3i"><img src="https://img.shields.io/github/stars/kh4sh3i?style=flat&logo=github"></a>
</h1>

# DevSecOps
Collection and Roadmap for everyone who wants DevSecOps, contains list of tools and methodologies


## 📜 Table of Contents
- [Resources](#resources)
  * [0. DevSecOps Overview](#0-devsecops-overview)
  * [1. Design](#1-design)
  * [2. Develop](#2-develop)
  * [3. Build](#3-build)
  * [4. Test](#4-test)
  * [5. Deploy](#5-deploy)
  * [6. Operate and Monitor](#6-operate-and-monitor)
- [Jenkins stage](#jenkins-stage)  
- [Tools](#-tools)
  * [0. Precommit](#pre-commit)
  * [1. Secrets management ](#secrets-management)
  * [2. SCA](#sca)
  * [3. SAST](#sast)
  * [4. DAST](#dast)
  * [5. Containers](#containers)
  * [6. Kubernetes](#kubernetes) 
- [Awesome resources](#awesome-resources)




## 📦 Resources
### 0. DevSecOps Overview
  - Overview
    1. [DevSecOps What Why And How (BlackHat USA-19)](https://i.blackhat.com/USA-19/Thursday/us-19-Shrivastava-DevSecOps-What-Why-And-How.pdf)
    2. [DevSecOps – Security and Test Automation (Mitre)](https://www.mitre.org/sites/default/files/publications/pr-19-0769-devsecops_security_test_automation-briefing.pdf)
### 1. Design
  - Development Lifecycle
    1. [OWASP's Software Assurance Maturity Model](https://github.com/OWASP/samm)
  - Threat Model
    1. [Threat Modeling by OWASP](https://owasp.org/www-community/Threat_Modeling)
    2. [OWASP Threat Dragon](https://threatdragon.github.io)
### 2. Develop
  - Secure Coding
    1. [Go-SCP / Go programming language secure coding practices guide](https://github.com/OWASP/Go-SCP)

### 3. Build  
  - SAST(Static Application Security Testing)
### 4. Test
  - DAST(Dynamic Application Security Testing)
  - Penetration testing
### 5. Deploy
  - Security Hardening & Config
    1. [CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks/)
  - Security Scanning
### 6. Operate and Monitor
  - RASP(Run-time Application Security Protection)
  - Security Patch
  - Security Audit
  - Security Monitor
  - Security Analysis




## Jenkins stage

* 1) sonarQube(SAST)
* 2) unit Test (Junit & Jacoco)
* 3) mutation Test (PIT)
* 4) Vulnerability scan -Docker 
  * dependency check
  * Trivy
  * OPA conftest
* 5) kubernetes deployment
  * kubesec scan
  * OPA scan
  * trivy
* 6) integration test
* 7) owasp zap (DAST) 
* 8) CIS benchmark (kube-bench)
* 9) monitoring

Tips :
* integration test check valid request and response api request
* we install openapi plugin in spring or other framework then get api-docs for pentesting woth zap proxy
* we use slack hook for send notification from jenkin, after any error or warm in report
* prometheus is a good notification manager and make graph with graphana
* use kiali for monitoring GUI kubernetis
* use mTls with istio for secure comunication betwean pods 
* falco is opensource cloud native runtime security project
* helm id package manager for kubernetis like yum 



## 🔩 Tools 

### Pre-commit


| Name | URL | Description |
| :---------- | :---------- | :---------- |
| **git-secrets** | [https://github.com/awslabs/git-secrets](https://github.com/awslabs/git-secrets) | AWS labs tool preventing you from committing secrets to a git repository  |
| **Talisman** | [https://github.com/thoughtworks/talisman](https://github.com/thoughtworks/talisman) | A tool to detect and prevent secrets from getting checked in |style=for-the-badge) |



### Secrets management 

| Name | URL | Description |
| :---------- | :---------- | :---------- |
| **GitLeaks** | [https://github.com/zricethezav/gitleaks](https://github.com/zricethezav/gitleaks) | Gitleaks is a scanning tool for detecting hardcoded secrets  |



### SCA 

| Name | URL | Description |
| :---------- | :---------- | :---------- | 
| **Snyk** | [https://github.com/snyk/snyk](https://github.com/snyk/snyk) | Snyk scans and monitors your projects for security vulnerabilities |
| **npm-check** | [https://www.npmjs.com/package/npm-check](https://www.npmjs.com/package/npm-check) | Check for outdated, incorrect, and unused dependencies. |



### SAST

| Name | URL | Description |
| :---------- | :---------- | :---------- |
| **Bandit** | [https://github.com/PyCQA/bandit ](https://github.com/PyCQA/bandit ) | Python specific SAST tool |
| **nodejsscan** | [https://github.com/ajinabraham/nodejsscan](https://github.com/ajinabraham/nodejsscan) | NodeJs SAST scanner with GUI |
| **SonarQube community** | [https://github.com/SonarSource/sonarqube](https://github.com/SonarSource/sonarqube) | Detect security issues in code review with Static Application Security Testing (SAST) |


### DAST

| Name | URL | Description | 
| :---------- | :---------- | :---------- |
| **Zap proxy** | [https://owasp.org/www-project-zap/](https://owasp.org/www-project-zap/) | Zap proxy providing various docker containers for CI/CD pipeline|
| **Nuclei** | [https://github.com/projectdiscovery/nuclei](https://github.com/projectdiscovery/nuclei) | Template based security scanning tool |


### Containers 

| Name | URL | Description |
| :---------- | :---------- | :---------- | 
| **Docker bench** | [https://github.com/docker/docker-bench-security ](https://github.com/docker/docker-bench-security ) | Docker benchmarking against CIS|
| **Trivy** | [https://github.com/aquasecurity/trivy](https://github.com/aquasecurity/trivy) | Comprehensive scanner for vulnerabilities in container images |


### Kubernetes 

| Name | URL | Description | 
| :---------- | :---------- | :---------- | 
| **kube-bench** | [https://github.com/aquasecurity/kube-bench ](https://github.com/aquasecurity/kube-bench ) | Kubernetes benchmarking tool|
| **kube-hunter** | [https://github.com/aquasecurity/kube-hunter](https://github.com/aquasecurity/kube-hunter) | Active scanner for k8s (purple)  |





## Awesome resources
* https://github.com/sottlmarek/DevSecOps
* https://github.com/devsecops/awesome-devsecops
* https://github.com/TaptuIT/awesome-devsecops
* https://github.com/hahwul/DevSecOps



