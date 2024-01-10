# Awesome Vulnerable Applications [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of various vulnerable by design applications


## Contents

- [Online](#Online)
- [Paid](#Paid)
- [Vulnerable VMs](#Vulnerable-VMs)
- [Cloud Security](#Cloud-Security)
- [SSO - Single Sign On](#SSO-Single-Sign-On)
- [Mobile Security](#Mobile-Security)
- [OWASP Top 10](#OWASP-Top-10)
    - [SQL Injection](#SQL-Injection)
    - [XSS Injection](#XSS-Injection)
    - [Server Side Request Forgery](#Server-Side-Request-Forgery)
    - [CORS Misconfiguration](#CORS-Misconfiguration)
    - [XXE Injection](#XXE-Injection)
    - [Request Smuggling](#Request-Smuggling)
- [Technologies](#Technologies)
    - [WordPress](#WordPress)
    - [Node.js](#Node.js)
    - [Firmware](#Firmware)
- [Uncategorized](#Uncategorized)

---

## Online

Online vulnerable app and CTFs

- [Hacker101 CTF](https://ctf.hacker101.com/)
- [Web Security Academy](https://portswigger.net/web-security)
- [Hack The Box](https://www.hackthebox.eu/)
- [Try Hack Me](https://tryhackme.com/)
- [CTFtime](https://ctftime.org/)
- [PWNABLE.KR](http://pwnable.kr/)
- [XSS game](https://xss-game.appspot.com)
- [Gin & Juice Shop](https://ginandjuice.shop/)

## Paid

Paid tranining courses

- [PentesterLab](https://pentesterlab.com/)

## Vulnerable VMs

- [Vulhub](https://github.com/vulhub/vulhub)
- [Exploit Exercises](https://exploit-exercises.lains.space/)
- [Metasploitable3](https://github.com/rapid7/metasploitable3) - Metasploitable3 is a VM that is built from the ground up with a large amount of security vulnerabilities.
- [Hackmyvm.eu](https://hackmyvm.eu/)

## Cloud Security

- [Kubernetes Goat](https://github.com/madhuakula/kubernetes-goat) - Kubernetes Goat is "Vulnerable by Design" Kubernetes Cluster. Designed to be an intentionally vulnerable cluster environment to learn and practice Kubernetes security.
- [CloudGoat](https://github.com/RhinoSecurityLabs/cloudgoat) - CloudGoat is Rhino Security Labs' "Vulnerable by Design" AWS deployment tool
- [CdkGoat - Vulnerable AWS CDK Infra](https://github.com/bridgecrewio/cdkgoat) - CdkGoat is Bridgecrew's "Vulnerable by Design" AWS CDK repository. 
- [Cfngoat - Vulnerable Cloudformation Template](https://github.com/bridgecrewio/cfngoat) - Cfngoat is Bridgecrew's "Vulnerable by Design" Cloudformation repository.
- [TerraGoat - Vulnerable Terraform Infra](https://github.com/bridgecrewio/terragoat) - TerraGoat is Bridgecrew's "Vulnerable by Design" Terraform repository.
- [caponeme - Capital One Breach](https://github.com/avishayil/caponeme) - Repository demonstrating the Capital One breach on your AWS account
- [WrongSecrets](https://github.com/commjoen/wrongsecrets) - WrongSecrets is "Vulnerable by Design" to show how to not handle secrets in Docker, Kubernetes and in the cloud (AWS/GCP/Azure).
- [AWSGoat](https://github.com/ine-labs/AWSGoat) - A Damn Vulnerable AWS Infrastructure
- [AzureGoat](https://github.com/ine-labs/AzureGoat) - A Damn Vulnerable Azure Infrastructure
- [IAM Vulnerable](https://github.com/BishopFox/iam-vulnerable) - Use Terraform to create your own vulnerable by design AWS IAM privilege escalation playground.
- [Sadcloud](https://github.com/nccgroup/sadcloud) - A tool for standing up (and tearing down!) purposefully insecure cloud infrastructure 
- [CNAPPgoat](https://github.com/ermetic-research/cnappgoat) - CNAPPgoat is a multi-cloud, vulnerable-by-design environment deployment tool. 
- [Unguard](https://github.com/dynatrace-oss/unguard) - An insecure cloud-native microservices demo application for Kubernetes

## SSO - Single Sign On

- [vulnerable-sso](https://github.com/dogangcr/vulnerable-sso) - vulnerable single sign on

## Mobile Security

- [Allsafe](https://github.com/t0thkr1s/allsafe) - Allsafe is an intentionally vulnerable application that contains various vulnerabilities.
- [InsecureBankv2](https://github.com/dineshshetty/Android-InsecureBankv2) - Vulnerable Android application for developers and security enthusiasts to learn about Android insecurities.
- [Vulnerable Kext](https://github.com/ant4g0nist/Vulnerable-Kext) - A WIP "Vulnerable by Design" kext for iOS/macOS to play & learn *OS kernel exploitation.
- [InjuredAndroid](https://github.com/B3nac/InjuredAndroid) - A vulnerable Android application that shows simple examples of vulnerabilities in a ctf style. 
- [Damn Vulnerable Bank](https://github.com/rewanthtammana/Damn-Vulnerable-Bank) -  Damn Vulnerable Bank is designed to be an intentionally vulnerable android application.
- [InsecureShop](https://github.com/optiv/InsecureShop) - An Intentionally designed Vulnerable Android Application built in Kotlin. 
- [AndroGoat](https://github.com/satishpatnayak/AndroGoat) - AndroGoat is purposely developed open source vulnerable/insecure app using Kotlin.
- [DIVA Android](https://github.com/payatu/diva-android) - Damn Insecure and vulnerable App for Android.
- [OVAA](https://github.com/oversecured/ovaa) - Oversecured Vulnerable Android App.
- [Vuldroid](https://github.com/jaiswalakshansh/Vuldroid) - Android Application covering various static and dynamic vulnerabilities.
- [Android Security Testing](https://github.com/RavikumarRamesh/hpAndro1337) - hpAndro1337 Application made in Kotlin with multiple vulnerabilities and a CTF.

## OWASP Top 10

- [Owasp Juice shop](https://github.com/bkimminich/juice-shop) - OWASP Juice Shop: Probably the most modern and sophisticated insecure web application
- [DVWA](https://github.com/ethicalhack3r/DVWA) - Damn Vulnerable Web Application (DVWA)
- [DSVW](https://github.com/stamparm/DSVW) - Damn Small Vulnerable Web
- [bWAPP](https://github.com/raesene/bWAPP) - This is just an instance of the OWASP bWAPP project as a docker container.
- [Xtreme Vulnerable Web Application](https://github.com/s4n7h0/xvwa) - XVWA is a badly coded web application written in PHP/MySQL that helps security enthusiasts to learn application security.
- [lazyweb](https://github.com/RamadhanAmizudin/lazyweb) - This web application is a demonstration of common server-side application flaws. Each of the vulnerabilities has its own difficulty rating.
- [OWASP Mutillidae II](https://github.com/webpwnized/mutillidae) - OWASP Mutillidae II is a free, open source, deliberately vulnerable web-application providing a target for web-security enthusiast.
- [Pentest_lab](https://github.com/oliverwiegers/pentest_lab) - Local penetration testing lab using docker-compose.
- [VulnLab](https://github.com/Yavuzlar/VulnLab) - A vulnerable web application lab using Docker
- [WebGoat](https://github.com/WebGoat/WebGoat) - WebGoat is a deliberately insecure application by OWASP for training purpose
- [VAmPI](https://github.com/erev0s/VAmPI) - Vulnerable REST API with OWASP top 10 vulnerabilities for security testing 

### SQL Injection

- [Yet Another Vulnerability Database](https://github.com/rtfpessoa/yavdb) - Yet Another Vulnerability Database

### XSS Injection

- [clicker-service - simulate XSS](https://gitlab.com/r00k/clicker-service) - Docker container that intakes post and then "clicks" the link. Intentionally vulnerable. To be used with vulnerable by design web apps to realistically simulate XSS and XSRF (CSRF).
- [XSSworm.dev](https://github.com/vavkamil/XSSworm.dev) - Self-replication contest
- [xssed](https://github.com/aj00200/xssed) - A set of XSS vulnerable PHP scripts for testing
- [xssable](https://github.com/kiwicom/xssable) - A vulnerable blogging platform used to demonstrate XSS vulnerabilities.

### Server Side Request Forgery

- [SSRF_Vulnerable_Lab](https://github.com/incredibleindishell/SSRF_Vulnerable_Lab) - This Lab contain the sample codes which are vulnerable to Server-Side Request Forgery attack

### CORS Misconfiguration

- [CORS-vulnerable-Lab](https://github.com/incredibleindishell/CORS-vulnerable-Lab) - Sample vulnerable code and its exploit code
- [CORS misconfiguration vulnerable Lab](https://github.com/incredibleindishell/CORS_vulnerable_Lab-Without_Database) - This Repository contains CORS misconfiguration related vulnerable codes.

### XXE Injection

- [XXE Lab](https://github.com/jbarone/xxelab) - A simple web app with a XXE vulnerability.
- [docker-java-xxe](https://github.com/pimps/docker-java-xxe) - Docker image to test XXE attacks in java with tomcat.


### Request Smuggling

- [Varnish HTTP/2 Request Smuggling](https://github.com/detectify/Varnish-H2-Request-Smuggling) - This repository a docker-compose file to setup a local environment that is vulnerable to CVE-2021-36740 Varnish HTTP/2 request smuggling.

## Technologies

### WordPress

- [DVWP](https://github.com/vavkamil/dvwp) - Damn Vulnerable WordPress

### Node.js

- [exploit-workshop](https://github.com/snyk/exploit-workshop) - A step by step workshop to exploit various vulnerabilities in Node.js and Java applications
- [DVNA](https://github.com/appsecco/dvna) - Damn Vulnerable NodeJS Application
- [Extreme Vulnerable Node Application](https://github.com/vegabird/xvna) - Extreme Vulnerable Node Application
- [dvws-node](https://github.com/snoopysecurity/dvws-node) - Damn Vulnerable Web Service is a vulnerable web service/API/application that can be used to learn webservices/API vulnerabilities.

### Firmware

- [DVRF](https://github.com/praetorian-code/DVRF) - The Damn Vulnerable Router Firmware Project
- [OWASP IoT Goat](https://github.com/OWASP/IoTGoat) - IoTGoat is a deliberately insecure firmware created to educate software developers and security professionals with testing commonly found vulnerabilities in IoT devices.
- [DVID](https://github.com/Vulcainreo/DVID) -  Damn Vulnerable IoT Device

## Uncategorized

- [LogSnare](https://github.com/sea-erkin/log-snare) - A playground for testing, preventing, and logging IDOR vulnerabilities.
- [GitHub Actions Goat](https://github.com/step-security/github-actions-goat) - Deliberately Vulnerable GitHub Actions CI/CD Environment
- [dvws - Damn Vulnerable Web Services](https://github.com/snoopysecurity/dvws) - Damn Vulnerable Web Services is an insecure web application with multiple vulnerable web service components that can be used to learn real world web service vulnerabilities.
- [Fuzzgoat](https://github.com/fuzzstati0n/fuzzgoat) - A vulnerable C program for testing fuzzers.
- [wavsep](https://github.com/sectooladdict/wavsep) - The Web Application Vulnerability Scanner Evaluation Project
- [leaky-repo](https://github.com/Plazmaz/leaky-repo) - Benchmarking repo for secrets scanning
- [OWASP SKF labs](https://github.com/blabla1337/skf-labs) - Repo for all the OWASP-SKF Docker lab examples
- [Vulnserver](https://github.com/stephenbradshaw/vulnserver) - Vulnerable server used for learning software exploitation
- [Damn-Vulnerable-GraphQL-Application](https://github.com/dolevf/Damn-Vulnerable-GraphQL-Application) - Damn Vulnerable GraphQL Application is an intentionally vulnerable implementation of Facebook's GraphQL technology, to learn and practice GraphQL Security.
- [Vulnerable-nginx](https://github.com/detectify/vulnerable-nginx) - An intentionally vulnerable NGINX setup 
- [Raspwn OS](https://github.com/alphacharlie/raspwn/) - The intentionally vulnerable image for the Raspberry Pi.
- [python_security](https://github.com/gbleaney/python_security) - This repository collects lists of security-relavent Python APIs, along with examples of exploits using those APIs 
- [OWASP-VWAD](https://github.com/OWASP/OWASP-VWAD) - The OWASP Vulnerable Web Applications Directory project (VWAD) is a comprehensive and well maintained registry of all known vulnerable web applications currently available. 
- [Vulhub](https://github.com/vulhub/vulhub) - Vulhub is an open-source collection of pre-built vulnerable docker environments. 
- [VulnDoge](https://github.com/burpOverflow/VulnDoge) - Web app for hunters 
- [CI/CD Goat](https://github.com/cider-security-research/cicd-goat) - Deliberately vulnerable CI/CD environment. Hack CI/CD pipelines, catch the flags.
- [Damn Vulnerable Thick Client](https://github.com/srini0x00/dvta) - Damn Vulnerable Thick Client App developed in C# .NET 
- [Damn Vulnerable RESTaurant](https://github.com/theowni/Damn-Vulnerable-RESTaurant-API-Game) - Intentionally vulnerable Web API game for learning and training purposes dedicated to developers, ethical hackers and security engineers.
- [VulnerableLightApp](https://github.com/Aif4thah/VulnerableLightApp) - .NET vulnerable REST API

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, vavkamil has waived all copyright and
related or neighboring rights to this work.
