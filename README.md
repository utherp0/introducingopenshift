# introducingopenshift

## Overview
Deployable self-paced workshops for introducing and using OpenShift 4 concepts (developer focused). This project will provide a deployable app (httpd based) that will have a number of self-paced introduction modules for enabling Developers on OpenShift.

## Format
This project will contain templates for generating additional modules. In order to keep source maintenance to a minimum a default index.htm file will be provided with linkage to all modules. If a subset is needed it is suggested you take a fork and add/modify an appropriate index.htm

## Design Goals
The project will provide static HTML that guides a user through interaction with an OpenShift platform. For simplicity the material is static HTML and will contain an introduction at the top each module stating 'what it is about', 'what you will learn' and 'duration of module'. Within the module material itself will be extensive explanation components, optional for reading but explaining in detail what the steps are doing.

## Module List
The initial drop of this course will contain:

- 000 High Level introduction to OpenShift Concepts (non-interactive)
- 001 Deploying your first Application
- 002 Deploying an Application from Source Code
- 003 Configuring an Application (replicas and environment variable) 
- 004 Deploying Multiple Applications
- 005 Injecting Configuration into Applications (using Config Maps)
- 006 Injecting Secure Configuration into Applications (using Secrets)
- 007 Networking of Applications
- 008 CI using Pipelines
- 009 CD using GitOps
