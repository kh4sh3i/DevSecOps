# DevSecOps
Collection and Roadmap for everyone who wants DevSecOps
This library contains list of tools and methodologies accompanied with resources. The main goal is to provide to the engineers a guide through opensource DevSecOps tooling

<h1 align="center">
  <br>
  <a href=""><img src="https://user-images.githubusercontent.com/13212227/99404580-2374f000-292f-11eb-9348-284f24cca88c.png" alt="" width="500px;"></a>
  <br>
  <img src="https://img.shields.io/badge/PRs-welcome-blue">
  <img src="https://img.shields.io/github/last-commit/kh4sh3i/DevSecOps">
  <img src="https://api.codacy.com/project/badge/Grade/e5fd334a431848dcb6ecdb3784fb5dfb">
  <a href="https://twitter.com/intent/follow?screen_name=kh4sh3i_"><img src="https://img.shields.io/twitter/follow/kh4sh3i_?style=flat&logo=twitter"></a>
  <a href="https://github.com/kh4sh3i"><img src="https://img.shields.io/github/stars/kh4sh3i?style=flat&logo=github"></a>
</h1>

> Roadmap for everyone who wants DevSecOps.

## 📜 Table of Contents
- [Roadmap](#-roadmap)
- [Tools](#-tools)
- [Resources](#resources)
  * [0. DevSecOps Overview](#0-devsecops-overview)
  * [1. Design](#1-design)
  * [2. Develop](#2-develop)
  * [3. Build](#3-build)
  * [4. Test](#4-test)
  * [5. Deploy](#5-deploy)
  * [6. Operate and Monitor](#6-operate-and-monitor)
- [Security of CICD](#security-of-cicd)
- [Awesome resources](#awesome-resources)


## 💭 Roadmap
![Roadmap](./DevSecOps.png)

## 🔩 Tools 
Spending a lot of time on applying DevSecOps is searching, comparing, and making decisions about tools. These tool lists are a good way to help you reduce unnecessary time and apply them quickly :sunglasses:

Open https://github.com/kh4sh3i_/DevSecOps/blob/main/tools/README.md

## 📦 Resources
### 0. DevSecOps Overview
  - Overview
    1. [DevSecOps in Wikipedia](https://en.wikipedia.org/wiki/DevOps#DevSecOps,_Shifting_Security_Left)
    2. [Zero to DevSecOps (OWASP Meetup)](https://owasp.org/www-chapter-belgium/assets/2019/2019-02-20/Zero-to-DevSecOps-OWASP-Meetup-02-19-19.pdf)
    3. [DevSecOps What Why And How (BlackHat USA-19)](https://i.blackhat.com/USA-19/Thursday/us-19-Shrivastava-DevSecOps-What-Why-And-How.pdf)
    4. [DevSecOps – Security and Test Automation (Mitre)](https://www.mitre.org/sites/default/files/publications/pr-19-0769-devsecops_security_test_automation-briefing.pdf)
### 1. Design
  - Development Lifecycle
    1. [SDL(Secure Development Lifecycle) by Microsoft](https://www.microsoft.com/en-us/securityengineering/sdl/practices)
    2. [OWASP's Software Assurance Maturity Model](https://github.com/OWASP/samm)
    3. [Building Security In Maturity Model (BSIMM)](https://www.bsimm.com/framework.html)
    4. [NIST's Secure Software Developerment Framework](https://csrc.nist.gov/CSRC/media/Publications/white-paper/2019/06/07/mitigating-risk-of-software-vulnerabilities-with-ssdf/draft/documents/ssdf-for-mitigating-risk-of-software-vulns-draft.pdf)
    5. [DevSecOps basics: 9 tips for shifting left (Gitlab)](https://about.gitlab.com/blog/2020/06/23/efficient-devsecops-nine-tips-shift-left/)
    6. [6 Ways to bring security to the speed of DevOps (Gitlab)](https://about.gitlab.com/blog/2019/10/31/speed-security-devops/)
  - Threat Model
    1. [What is Threat Modeling / Wikipedia](https://en.wikipedia.org/wiki/Threat_model)
    2. [Threat Modeling by OWASP](https://owasp.org/www-community/Threat_Modeling)
    3. [Application Threat Modeling by OWASP](https://owasp.org/www-community/Application_Threat_Modeling)
    4. [Agile Threat Modeling Toolkit](https://threagile.io)
    5. [OWASP Threat Dragon](https://threatdragon.github.io)
### 2. Develop
  - Secure Coding
    1. [Secure coding guide by Apple](https://developer.apple.com/library/archive/documentation/Security/Conceptual/SecureCodingGuide/Introduction.html)
    2. [Secure Coding Guidelines for Java SE](https://www.oracle.com/java/technologies/javase/seccodeguide.html)
    3. [Go-SCP / Go programming language secure coding practices guide](https://github.com/OWASP/Go-SCP)
    4. [Android App security best practices by Google](https://developer.android.com/topic/security/best-practices)
    5. [Securing Rails Applications](https://guides.rubyonrails.org/security.html)
### 3. Build  
  - SAST(Static Application Security Testing)
    1. [Scan Source Code using Static Application Security Testing (SAST) with SonarQube, Part 1](https://medium.com/nycdev/scan-your-source-code-for-vulnerabilities-using-static-application-security-testing-sast-with-5f8ee1fdf9aa)
    2. [Announcing third-party code scanning tools: static analysis & developer security training](https://github.blog/2020-10-05-announcing-third-party-code-scanning-tools-static-analysis-and-developer-security-training/)
### 4. Test
  - DAST(Dynamic Application Security Testing)
    1. [Dynamic Application Security Testing with ZAP and GitHub Actions](https://www.zaproxy.org/blog/2020-05-15-dynamic-application-security-testing-with-zap-and-github-actions/) 
    2. [Dynamic Application Security Testing (DAST) in Gitlab](https://docs.gitlab.com/ee/user/application_security/dast/)
    3. [DAST using pdiscoveryio Nuclei (github action)](https://github.com/secopslab/nuclei-action)
    4. [ZAPCon 2021-Democratizing ZAP with test automation and domain specific languages](https://youtu.be/jimW-R6_F4U)
  - Penetration testing
    1. [Penetration Testing at DevSecOps Speed](https://securityboulevard.com/2019/04/penetration-testing-at-devsecops-speed/)
### 5. Deploy
  - Security Hardening & Config
    1. [CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks/)
    2. [DevSecOps in Kubernetes](https://cloudblogs.microsoft.com/opensource/2019/07/22/devsecops-in-kubernetes/)
  - Security Scanning
    1. [Best practices for scanning images (docker)](https://docs.docker.com/develop/scan-images/)
### 6. Operate and Monitor
  - RASP(Run-time Application Security Protection)
    1. [Runtime Application Self-Protection by rapid7](https://www.rapid7.com/fundamentals/runtime-application-self-protection/)
    2. [Jumpstarting your devsecops - Pipeline with IAST and RASP](https://2018.appsec.eu/presos/DevOps_Jumpstarting-Your-DevSecOps_Jeff-Williams_AppSecEU2018.pdf)
  - Security Patch
  - Security Audit
  - Security Monitor
  - Security Analysis

## Security of CICD
- Github Actions
    1. [Security hardening for GitHub Actions](https://docs.github.com/en/actions/security-guides/security-hardening-for-github-actions)
    2. [Github Actions Security Best Practices](https://engineering.salesforce.com/github-actions-security-best-practices-b8f9df5c75f5)
    3. [GitHub Actions Security Best Practices [cheat sheet included]](https://blog.gitguardian.com/github-actions-security-cheat-sheet/)
- Jenkins
    1. [Securing Jenkins](https://www.jenkins.io/doc/book/security/)
    2. [Securing Jenkins CI Systems by SANS](https://www.sans.org/white-papers/36872/)
    3. [DEPRECATED/chef-jenkins-hardening](https://github.com/dev-sec/chef-jenkins-hardening)

## Awesome resources
* https://github.com/sottlmarek/DevSecOps
* https://github.com/devsecops/awesome-devsecops
* https://github.com/TaptuIT/awesome-devsecops
* https://github.com/hahwul/DevSecOps























# Table of Contents


- [Tooling](#tooling)
- [Precommit and threat modeling](#pre-commit-time-tools)
- [SAST](#sast)
- [DAST](#dast)
- [Orchestration](#orchestration)
- [Supply chain and dependencies](#oss-and-dependency-management)
- [Infrastructure as code](#infrastructure-as-code-security)
- [Containers security](#containers)
- [Kubernetes](#kubernetes) 
- [Cloud](#multi-cloud)
- [Chaos engineering](#chaos-engineering)
- [Policy as code](#policy-as-code)


# Tooling

## Pre-commit time tools

In this section you can find lifecycle helpers, precommit hook tools and threat modeling tools. Threat modeling tools are specific category by themselves allowing you to simulate and discover potential gaps before you start to develop the software or during the process.

Modern DevSecOps tools allow using Threat modeling as code or generation of threat models based on the existing code annotations. 

| Name | URL | Description |
| :---------- | :---------- | :---------- |
| **git-secrets** | [https://github.com/awslabs/git-secrets](https://github.com/awslabs/git-secrets) | AWS labs tool preventing you from committing secrets to a git repository  |
| **git-hound** | [https://github.com/tillson/git-hound](https://github.com/tillson/git-hound) | Searchers secrets in git |
| **goSDL** | [https://github.com/slackhq/goSDL](https://github.com/slackhq/goSDL) |Security Development Lifecycle checklist   |
| **ThreatPlaybook** | [https://github.com/we45/ThreatPlaybook](https://github.com/we45/ThreatPlaybook) |Threat modeling as code   |
| **Threat Dragon** | [https://github.com/OWASP/threat-dragon](https://github.com/OWASP/threat-dragon) | OWASP Threat modeling tool  |
| **threatspec** | [https://github.com/threatspec/threatspec](https://github.com/threatspec/threatspec) | Threat modeling as code  |
| **pytm** | [https://github.com/izar/pytm](https://github.com/izar/pytm) | A Pythonic framework for threat modeling  |
| **Threagile** | [https://github.com/Threagile/threagile](https://github.com/Threagile/threagile) | A Go framework for threat modeling  |
| **MAL-lang** | [https://mal-lang.org/#what ](https://mal-lang.org/#what ) | A language to create cyber threat modeling systems for specific domains  |
| **Microsoft Threat modeling tool** | [https://docs.microsoft.com/en-us/azure/security/develop/threat-modeling-tool](https://docs.microsoft.com/en-us/azure/security/develop/threat-modeling-tool) | Microsoft threat modeling tool  |
| **Talisman** | [https://github.com/thoughtworks/talisman](https://github.com/thoughtworks/talisman) | A tool to detect and prevent secrets from getting checked in |style=for-the-badge) |
| **SEDATED** | [https://github.com/OWASP/SEDATED](https://github.com/OWASP/SEDATED) | The SEDATED® Project (Sensitive Enterprise Data Analyzer To Eliminate Disclosure) focuses on preventing sensitive data such as user credentials and tokens from being pushed to Git. |
| **Sonarlint** | [https://github.com/SonarSource/sonarlint-core](https://github.com/SonarSource/sonarlint-core) |  Sonar linting utility for IDE |
| **DevSkim** | [https://github.com/microsoft/DevSkim](https://github.com/microsoft/DevSkim) |  DevSkim is a framework of IDE extensions and language analyzers that provide inline security analysis |
| **detect-secrets** | [https://github.com/Yelp/detect-secrets](https://github.com/Yelp/detect-secrets) |  Detects secrets in your codebase |
| **tflint** | [https://github.com/terraform-linters/tflint](https://github.com/terraform-linters/tflint) | A Pluggable Terraform Linter | 
## Secrets management 
Secrets management includes managing, versioning, encryption, discovery, rotating, provisioning of passwords, certificates, configuration values and other types of secrets. 

| Name | URL | Description |
| :---------- | :---------- | :---------- |
| **GitLeaks** | [https://github.com/zricethezav/gitleaks](https://github.com/zricethezav/gitleaks) | Gitleaks is a scanning tool for detecting hardcoded secrets  |
| **ggshield** | [https://github.com/gitguardian/ggshield](https://github.com/gitguardian/ggshield) | GitGuardian shield (ggshield) is a CLI application that runs in your local environment or in a CI environment and helps you detect more than 350+ types of secrets and sensitive files.  |
| **TruffleHog** | [https://github.com/trufflesecurity/truffleHog](https://github.com/trufflesecurity/truffleHog) | TruffleHog is a scanning tool for detecting hardcoded secrets  |
| **Hashicorp Vault** | [https://github.com/hashicorp/vault](https://github.com/hashicorp/vault) | Hashicorp Vault secrets management  |
| **Mozilla SOPS** | [https://github.com/mozilla/sops ](https://github.com/mozilla/sops ) | Mozilla Secrets Operations  |
| **AWS secrets manager GH action** | [https://github.com/marketplace/actions/aws-secrets-manager-actions](https://github.com/marketplace/actions/aws-secrets-manager-actions)| AWS secrets manager [docs](https://aws.amazon.com/secrets-manager/) |
| **GitRob** | [https://github.com/michenriksen/gitrob](https://github.com/michenriksen/gitrob) | Gitrob is a tool to help find potentially sensitive files pushed to public repositories on Github  |
| **git-wild-hunt** | [https://github.com/d1vious/git-wild-hunt](https://github.com/d1vious/git-wild-hunt ) | A tool to hunt for credentials in the GitHub |
| **aws-vault** | [https://github.com/99designs/aws-vault](https://github.com/99designs/aws-vault) | AWS Vault is a tool to securely store and access AWS credentials in a development environment |
| **Knox** | [https://github.com/pinterest/knox](https://github.com/pinterest/knox) | Knox is a service for storing and rotation of secrets, keys, and passwords used by other services |
| **Chef vault** | [https://github.com/chef/chef-vault](https://github.com/chef/chef-vault) |  allows you to encrypt a Chef Data Bag Item |
| **Ansible vault** | [Ansible vault docs](https://docs.ansible.com/ansible/latest/cli/ansible-vault.html#ansible-vault) |  Encryption/decryption utility for Ansible data files |

## OSS and Dependency management

Dependency security testing and analysis is very important part of discovering supply chain attacks. SBOM creation and following dependency scanning (Software composition analysis) is critical part of continuous integration (CI). Data series and data trends tracking should be part of CI tooling. You need to know what you produce and what you consume in context of libraries and packages. 

| Name | URL | Description |
| :---------- | :---------- | :---------- | 
| **CycloneDX** | [https://github.com/orgs/CycloneDX/repositories](https://github.com/orgs/CycloneDX/repositories) | CycloneDX format for **SBOM** |
| **SPDX** | [https://github.com/spdx/spdx-spec](https://github.com/spdx/spdx-spec) | SPDX format for **SBOM** - Software Package Data Exchange |
| **Snyk** | [https://github.com/snyk/snyk](https://github.com/snyk/snyk) | Snyk scans and monitors your projects for security vulnerabilities |
| **vulncost** | [https://github.com/snyk/vulncost](https://github.com/snyk/vulncost) | Security Scanner for VS Code |
| **Dependency Combobulator** | [https://github.com/apiiro/combobulator](https://github.com/apiiro/combobulator) | Dependency-related attacks detection and prevention through heuristics and insight engine (support multiple dependency schemes) | 
| **DependencyTrack** | [https://github.com/DependencyTrack/dependency-track](https://github.com/DependencyTrack/dependency-track) | Dependency security tracking platform |
| **DependencyCheck** | [https://github.com/jeremylong/DependencyCheck](https://github.com/jeremylong/DependencyCheck) | Simple dependency security scanner good for CI |
| **Retire.js** | [https://github.com/retirejs/retire.js/](https://github.com/retirejs/retire.js/) | Helps developers to detect the use of JS-library versions with known vulnerabilities |
| **PHP security checker** | [https://github.com/fabpot/local-php-security-checker](https://github.com/fabpot/local-php-security-checker) | Check vulnerabilities in PHP dependencies |
| **bundler-audit** | [https://github.com/rubysec/bundler-audit](https://github.com/rubysec/bundler-audit) | Patch-level verification for bundler |
| **gemnasium** | [https://gitlab.com/gitlab-org/security-products/analyzers/gemnasium ](https://gitlab.com/gitlab-org/security-products/analyzers/gemnasium ) | Dependency Scanning Analyzer based on Gemnasium || 
| **Dependabot** | [https://github.com/dependabot/dependabot-core](https://github.com/dependabot/dependabot-core) | Automated dependency updates built into GitHub providing security alerts |
| **Renovatebot** | [https://github.com/renovatebot/renovate](https://github.com/renovatebot/renovate) | Automated dependency updates, patches multi-platform and multi-language |
| **npm-check** | [https://www.npmjs.com/package/npm-check](https://www.npmjs.com/package/npm-check) | Check for outdated, incorrect, and unused dependencies. |

## Supply chain specific tools 

Supply chain is often the target of attacks. Which libraries you use can have a massive impact on security of the final product (artifacts). CI (continuous integration) must be monitored inside the tasks and jobs in pipeline steps. Integrity checks must be stored out of the system and in ideal case several validation runs with comparison of integrity hashes / or attestation must be performed. 

| Name | URL | Description | 
| :---------- | :---------- | :---------- |
| **Tekton chains** | [https://github.com/tektoncd/chains](https://github.com/tektoncd/chains/) | Kubernetes Custom Resource Definition (CRD) controller that allows you to manage your supply chain security in Tekton. |
| **in-toto** | [https://github.com/in-toto/attestation/tree/v0.1.0/spec](https://github.com/in-toto/attestation/tree/v0.1.0/spec) | An in-toto attestation is authenticated metadata about one or more software artifacts |
| **SLSA** | [Official GitHub link](https://github.com/slsa-framework/slsa/blob/main/docs/index.md ) | Supply-chain Levels for Software Artifacts |
| **kritis** | [https://github.com/grafeas/kritis](https://github.com/grafeas/kritis) | Solution for securing your software supply chain for Kubernetes apps |
| **ratify** | [https://github.com/deislabs/ratify](https://github.com/deislabs/ratify) | Artifact Ratification Framework |


## SAST

Static code review tools working with source code and looking for known patterns and relationships of methods, variables, classes and libraries. SAST works with the raw code and usually not with build packages. 

| Name | URL | Description |
| :---------- | :---------- | :---------- |
| **Brakeman** | [https://github.com/presidentbeef/brakeman](https://github.com/presidentbeef/brakeman) | Brakeman is a static analysis tool which checks Ruby on Rails applications for security vulnerabilities|
| **Semgrep** | [https://semgrep.dev/](https://semgrep.dev/) | Hi-Quality Open source, works on 17+ languages |
| **Bandit** | [https://github.com/PyCQA/bandit ](https://github.com/PyCQA/bandit ) | Python specific SAST tool |
| **libsast** | [https://github.com/ajinabraham/libsast ](https://github.com/ajinabraham/libsast ) | Generic SAST for Security Engineers. Powered by regex based pattern matcher and semantic aware semgrep |
| **ESLint** | [https://eslint.org/](https://eslint.org/) | Find and fix problems in your JavaScript code | | 
| **nodejsscan** | [https://github.com/ajinabraham/nodejsscan](https://github.com/ajinabraham/nodejsscan) | NodeJs SAST scanner with GUI |
| **FindSecurityBugs** | [https://find-sec-bugs.github.io/](https://find-sec-bugs.github.io/) | The SpotBugs plugin for security audits of Java web applications |
| **SonarQube community** | [https://github.com/SonarSource/sonarqube](https://github.com/SonarSource/sonarqube) | Detect security issues in code review with Static Application Security Testing (SAST) |
| **gosec** | [https://github.com/securego/gosec](https://github.com/securego/gosec) | Inspects source code for security problems by scanning the Go AST. |
**Note:** Semgrep is free CLI tool, however some rulesets (https://semgrep.dev/r) are having various licences, some can be free to use and can be commercial.  

OWASP curated list of SAST tools : https://owasp.org/www-community/Source_Code_Analysis_Tools 

## DAST

Dynamic application security testing (DAST) is a type of application testing (in most cases web) that checks your application from the outside by active communication and analysis of the responses based on injected inputs. DAST tools rely on inputs and outputs to operate. A DAST tool uses these to check for security problems while the software is actually running and is actively deployed on the server (or serverless function).

| Name | URL | Description | 
| :---------- | :---------- | :---------- |
| **Zap proxy** | [https://owasp.org/www-project-zap/](https://owasp.org/www-project-zap/) | Zap proxy providing various docker containers for CI/CD pipeline|
| **Wapiti** | [https://github.com/wapiti-scanner/wapiti ](https://github.com/wapiti-scanner/wapiti ) | Light pipeline ready scanning tool |
| **Nuclei** | [https://github.com/projectdiscovery/nuclei](https://github.com/projectdiscovery/nuclei) | Template based security scanning tool |
| **purpleteam** | [https://github.com/purpleteam-labs/purpleteam](https://github.com/purpleteam-labs/purpleteam) | CLI DAST tool incubator project |style=for-the-badge) | 
| **oss-fuzz** | [https://github.com/google/oss-fuzz ](https://github.com/google/oss-fuzz ) | OSS-Fuzz: Continuous Fuzzing for Open Source Software |
| **nikto** | [https://github.com/sullo/nikto](https://github.com/sullo/nikto) | Nikto web server scanner |
| **skipfish** | [https://code.google.com/archive/p/skipfish/](https://code.google.com/archive/p/skipfish/) | Skipfish is an active web application security reconnaissance tool|


## Continuous deployment security

| Name | URL | Description | 
| :---------- | :---------- | :---------- | 
| **SecureCodeBox** | [https://github.com/secureCodeBox/secureCodeBox](https://github.com/secureCodeBox/secureCodeBox) | Toolchain for continuous scanning of applications and infrastructure |
| **OpenSCAP** | [https://github.com/OpenSCAP/openscap](https://github.com/OpenSCAP/openscap) | Open Source Security Compliance Solution |
| **ThreatMapper** | [https://github.com/deepfence/ThreatMapper](https://github.com/deepfence/ThreatMapper) | ThreatMapper hunts for vulnerabilities in your production platforms, and ranks these vulnerabilities based on their risk-of-exploit. |

## Kubernetes 

| Name | URL | Description | 
| :---------- | :---------- | :---------- | 
| **KubiScan** | [https://github.com/cyberark/KubiScan](https://github.com/cyberark/KubiScan) | A tool for scanning Kubernetes cluster for risky permissions |
| **Kubeaudit** | [https://github.com/Shopify/kubeaudit](https://github.com/Shopify/kubeaudit) | Audit Kubernetes clusters for various different security concerns |
| **Kubescape** | [https://github.com/armosec/kubescape](https://github.com/armosec/kubescape) |  The first open-source tool for testing if Kubernetes is deployed according to the NSA-CISA and the MITRE ATT&CK®. |
| **kubesec** | [https://github.com/controlplaneio/kubesec](https://github.com/controlplaneio/kubesec) | Security risk analysis for Kubernetes resources |
| **kube-bench** | [https://github.com/aquasecurity/kube-bench ](https://github.com/aquasecurity/kube-bench ) | Kubernetes benchmarking tool|
| **kube-score** | [https://github.com/zegl/kube-score](https://github.com/zegl/kube-score) | Static code analysis of your Kubernetes object definitions |
| **kube-hunter** | [https://github.com/aquasecurity/kube-hunter](https://github.com/aquasecurity/kube-hunter) | Active scanner for k8s (purple)  |
| **Calico** | [https://github.com/projectcalico/calico](https://github.com/projectcalico/calico) | Calico is an open source networking and network security solution for containers  |
| **Kyverno** | [https://github.com/kyverno/kyverno/](https://github.com/kyverno/kyverno) | Kyverno is a policy engine designed for Kubernetes |
| **Krane** | [https://github.com/appvia/krane](https://github.com/appvia/krane) | Simple Kubernetes RBAC static analysis tool |
| **Starboard** | [https://github.com/aquasecurity/starboard](https://github.com/aquasecurity/starboard ) | Starboard inegrates security tools by outputs into Kubernetes CRDs |
| **Gatekeeper** | [https://github.com/open-policy-agent/gatekeeper](https://github.com/open-policy-agent/gatekeeper) | Open policy agent gatekeeper for k8s |
| **Inspektor-gadget** | [https://github.com/kinvolk/inspektor-gadget](https://github.com/kinvolk/inspektor-gadget ) | Collection of tools (or gadgets) to debug and inspect k8s |
| **kube-linter** | [https://github.com/stackrox/kube-linter ](https://github.com/stackrox/kube-linter) | Static analysis for Kubernetes |
| **mizu-api-traffic-viewer** | [https://github.com/up9inc/mizu](https://github.com/up9inc/mizu) | A simple-yet-powerful API traffic viewer for Kubernetes enabling you to view all API communication between microservices to help your debug and troubleshoot regressions. |
| **HelmSnyk** | [https://github.com/snyk-labs/helm-snyk](https://github.com/snyk-labs/helm-snyk) | The Helm plugin for Snyk provides a subcommand for testing the images. |
| **Kubewarden** | [https://github.com/orgs/kubewarden/repositories](https://github.com/orgs/kubewarden/repositories) | Policy as code for kubernetes from SUSE. |
| **Kubernetes-sigs BOM** | [https://github.com/kubernetes-sigs/bom](https://img.shields.io/github/stars/kubernetes-sigs/bom) |Kubernetes BOM generator |
| **Capsule** | [https://github.com/clastix/capsule](https://github.com/clastix/capsule) | A multi-tenancy and policy-based framework for Kubernetes |
| **Badrobot** | [https://github.com/controlplaneio/badrobot](https://github.com/controlplaneio/badrobot) | Badrobot is a Kubernetes Operator audit tool |

## Containers 

| Name | URL | Description |
| :---------- | :---------- | :---------- | 
| **Harbor** | [https://github.com/goharbor/harbor](https://github.com/goharbor/harbor) | Trusted cloud native registry project|
| **Anchore** | [https://github.com/anchore/anchore-engine](https://github.com/anchore/anchore-engine) | Centralized service for inspection, analysis, and certification of container images |
| **Clair** | [https://github.com/quay/clair](https://github.com/quay/clair) | Docker vulnerability scanner|
| **Deepfence ThreatMapper** | [https://github.com/deepfence/ThreatMapper](https://github.com/deepfence/ThreatMapper) | Apache v2, powerful runtime vulnerability scanner for kubernetes, virtual machines and serverless. | 
| **Docker bench** | [https://github.com/docker/docker-bench-security ](https://github.com/docker/docker-bench-security ) | Docker benchmarking against CIS|
| **Falco** | [https://github.com/falcosecurity/falco](https://github.com/falcosecurity/falco) | Container runtime protection |
| **Trivy** | [https://github.com/aquasecurity/trivy](https://github.com/aquasecurity/trivy) | Comprehensive scanner for vulnerabilities in container images |
| **Notary** | [https://github.com/notaryproject/notary](https://github.com/notaryproject/notary) | Docker signing|
| **Cosign** | [https://github.com/sigstore/cosign](https://github.com/sigstore/cosign) | Container signing|
| **watchtower** | [https://github.com/containrrr/watchtower](https://github.com/containrrr/watchtower) | Updates the running version of your containerized app |

## Multi-Cloud 

| Name | URL | Description |
| :---------- | :---------- | :---------- | 
| **Cloudsploit** | [https://github.com/aquasecurity/cloudsploit](https://github.com/aquasecurity/cloudsploit) | Detection of security risks in cloud infrastructure |
| **ScoutSuite** | [https://github.com/nccgroup/ScoutSuite](https://github.com/nccgroup/ScoutSuite) | NCCgroup mutlicloud scanning tool |
| **CloudCustodian** | [https://github.com/cloud-custodian/cloud-custodian/](https://github.com/cloud-custodian/cloud-custodian/) | Multicloud security analysis framework |
| **CloudGraph** | [https://github.com/cloudgraphdev/cli](https://github.com/cloudgraphdev/cli) | GraphQL API + Security for AWS, Azure, GCP, and K8s |


## AWS 

AWS specific DevSecOps tooling. Tools here cover different areas like inventory management, misconfiguration scanning or IAM roles and policies review. 

| Name | URL | Description | 
| :---------- | :---------- | :---------- |
| **Dragoneye** | [https://github.com/indeni/dragoneye](https://github.com/indeni/dragoneye) | Dragoneye Indeni AWS scanner |
| **Prowler** | [https://github.com/toniblyx/prowler](https://github.com/toniblyx/prowler) | Prowler is a command line tool that helps with AWS security assessment, auditing, hardening and incident response. |
| **aws-inventory** | [https://github.com/nccgroup/aws-inventory](https://github.com/nccgroup/aws-inventory) | Helps to discover all AWS resources created in an account|
| **PacBot** | [https://github.com/tmobile/pacbot](https://github.com/tmobile/pacbot) | Policy as Code Bot (PacBot)|
| **Komiser** | [https://github.com/mlabouardy/komiser](https://github.com/mlabouardy/komiser) | Monitoring dashboard for costs and security|
| **Cloudsplaining** | [https://github.com/salesforce/cloudsplaining](https://github.com/salesforce/cloudsplaining) | IAM analysis framework |
| **ElectricEye** | [https://github.com/jonrau1/ElectricEye](https://github.com/jonrau1/ElectricEye) | Continuously monitor your AWS services for configurations |
| **Cloudmapper** | [https://github.com/duo-labs/cloudmapper](https://github.com/duo-labs/cloudmapper ) | CloudMapper helps you analyze your Amazon Web Services (AWS) environments |
| **cartography** | [https://github.com/lyft/cartography](https://github.com/lyft/cartography) | Consolidates AWS infrastructure assets and the relationships between them in an intuitive graph |
| **policy_sentry** | [https://github.com/salesforce/policy_sentry](https://github.com/salesforce/policy_sentry ) | IAM Least Privilege Policy Generator |
| **AirIAM** | [https://github.com/bridgecrewio/AirIAM](https://github.com/bridgecrewio/AirIAM) | IAM Least Privilege anmalyzer and Terraformer |
| **StreamAlert** | [https://github.com/airbnb/streamalert](https://github.com/airbnb/streamalert ) | AirBnB serverless, real-time data analysis framework which empowers you to ingest, analyze, and alert  |
| **CloudQuery** | [https://github.com/cloudquery/cloudquery/](https://github.com/cloudquery/cloudquery/) | AirBnB serverless, real-time data analysis framework which empowers you to ingest, analyze, and alert  |
| **S3Scanner** | [https://github.com/sa7mon/S3Scanner/](https://github.com/cloudquery/cloudquery/) | A tool to find open S3 buckets and dump their contents  |
| **aws-iam-authenticator** | [https://github.com/kubernetes-sigs/aws-iam-authenticator/](https://github.com/kubernetes-sigs/aws-iam-authenticator/) | A tool to use AWS IAM credentials to authenticate to a Kubernetes cluster |
| **kube2iam** | [https://github.com/jtblin/kube2iam/](https://github.com/jtblin/kube2iam/) | A tool to use AWS IAM credentials to authenticate to a Kubernetes cluster |
| **AWS open source security samples** | [Official AWS opensource repo](https://github.com/orgs/aws-samples/repositories?language=&q=security&sort=&type=) |Collection of official AWS open-source resources | 
| **AWS Firewall factory** | [Globaldatanet FMS automation](https://github.com/globaldatanet/aws-firewall-factory) |Deploy, update, and stage your WAFs while managing them centrally via FMS |
| **Parliment** | [Parliment](https://github.com/duo-labs/parliament) | Parliament is an AWS IAM linting library | 
| **Yor** | [Yor](https://github.com/bridgecrewio/yor) | Adds informative and consistent tags across infrastructure-as-code frameworks such as Terraform, CloudFormation, and Serverless |


## Google cloud platform 

GCP specific DevSecOps tooling. Tools here cover different areas like inventory management, misconfiguration scanning or IAM roles and policies review. 

| Name | URL | Description | Meta | 
| :---------- | :---------- | :---------- | :----------: |
| **Forseti** | [https://github.com/forseti-security/forseti-security](https://github.com/forseti-security/forseti-security) | Complex security orchestration and scanning platform | 


## Policy as code

Policy as code is the idea of writing code in a high-level language to manage and automate policies. By representing policies as code in text files, proven software development best practices can be adopted such as version control, automated testing, and automated deployment. (Source: https://docs.hashicorp.com/sentinel/concepts/policy-as-code)

| Name | URL | Description | Meta | 
| :---------- | :---------- | :---------- | :----------: |
| **Open Policy agent** | [https://github.com/open-policy-agent/opa](https://github.com/open-policy-agent/opa) | General-purpose policy engine that enables unified, context-aware policy enforcement across the entire stack |
| **Inspec** | [https://github.com/inspec/inspec](https://github.com/inspec/inspec) | Chef InSpec is an open-source testing framework for infrastructure with a human- and machine-readable language for specifying compliance, security and policy requirements. |
| **Cloud Formation guard** | [https://github.com/aws-cloudformation/cloudformation-guard](https://github.com/aws-cloudformation/cloudformation-guard) | Cloud Formation policy as code |


## Chaos engineering

Chaos Engineering is the discipline of experimenting on a system in order to build confidence in the system’s capability to withstand turbulent conditions in production.

Reading and manifestos: https://principlesofchaos.org/

| Name | URL | Description | Meta | 
| :---------- | :---------- | :---------- | :----------: |
| **chaos-mesh** | [https://github.com/chaos-mesh/chaos-mesh](https://github.com/chaos-mesh/chaos-mesh) | It is a cloud-native Chaos Engineering platform that orchestrates chaos on Kubernetes environments |
| **Chaos monkey** | [https://netflix.github.io/chaosmonkey/](https://netflix.github.io/chaosmonkey/) | Chaos Monkey is responsible for randomly terminating instances in production to ensure that engineers implement their services to be resilient to instance failures. |
| **chaoskube** | [https://github.com/linki/chaoskube ](https://github.com/linki/chaoskube ) | Test how your system behaves under arbitrary pod failures. |
| **Kube-Invaders** | [https://github.com/lucky-sideburn/KubeInvaders](https://github.com/lucky-sideburn/KubeInvaders) | Gamified chaos engineering tool for Kubernetes |
| **kube-monkey** | [https://github.com/asobti/kube-monkey](https://github.com/asobti/kube-monkey) | Gamified chaos engineering tool for Kubernetes |
| **Gremlin** | [https://github.com/gremlin/gremlin-python](https://github.com/gremlin/gremlin-python) | Chaos enginnering SaaS platform with free plan and some open source libraries |
| **AWS FIS samples** | [https://github.com/aws-samples/aws-fault-injection-simulator-samples](https://github.com/aws-samples/aws-fault-injection-simulator-samples) | AWS Fault injection simulator samples |
| **CloudNuke** | [https://github.com/gruntwork-io/cloud-nuke](https://github.com/gruntwork-io/cloud-nuke) | CLI tool to delete all resources in an AWS account |

## Infrastructure as code security 

Scanning your infrastructure when it is only code helps shift-left the security. Many tools offer in IDE scanning and providing real-time advisory do Cloud engineers. 

| Name | URL | Description |
| :---------- | :---------- | :---------- |
| **KICS** | [https://github.com/Checkmarx/kics](https://github.com/Checkmarx/kics) | Checkmarx security testing opensource for IaC |
| **Checkov** | [https://github.com/bridgecrewio/checkov](https://github.com/bridgecrewio/checkov) | Checkov is a static code analysis tool for infrastructure-as-code |
| **tfsec** | [https://github.com/aquasecurity/tfsec](https://github.com/aquasecurity/tfsec) | tfsec uses static analysis of your terraform templates to spot potential security issues. Now with terraform CDK support |
| **terrascan** | [https://github.com/accurics/terrascan](https://github.com/accurics/terrascan) | Terrascan is a static code analyzer for Infrastructure as Code |
| **cfsec** | [https://github.com/aquasecurity/cfsec](https://github.com/aquasecurity/cfsec) | cfsec scans CloudFormation configuration files for security issues |
| **cfn_nag** | [https://github.com/stelligent/cfn_nag](https://github.com/stelligent/cfn_nag) |  Looks for insecure patterns in CloudFormation |
| **Sysdig IaC scanner action** | [https://github.com/sysdiglabs/cloud-iac-scanner-action](https://github.com/sysdiglabs/cloud-iac-scanner-action) |  Scans your repository with Sysdig IAC Scanner and report the vulnerabilities. |

## Orchestration 

Event driven security help to drive, automate and execute tasks for security processes. The tools here and not dedicated security tools but are helping to automate and orchestrate security tasks or are part of most modern security automation frameworks or tools. 

| Name | URL | Description | Meta |
| :---------- | :---------- | :---------- | :----------: |
| **StackStorm** | [https://github.com/StackStorm/st2](https://github.com/StackStorm/st2) | Platform for integration and automation across services and tools supporting event driven security |
| **Camunda** | [https://github.com/camunda/camunda-bpm-platform](https://github.com/camunda/camunda-bpm-platform) | Workflow and process automation |
| **DefectDojo** | [https://github.com/DefectDojo/django-DefectDojo](https://github.com/DefectDojo/django-DefectDojo) | Security orchestration and vulnerability management platform |

