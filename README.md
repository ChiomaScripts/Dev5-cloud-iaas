# Cloud Infrastructure & Java Application Deployment

Provisioning, configuring, and deploying a Java application on a Linux-based cloud server using DigitalOcean.

## Overview

This project demonstrates the fundamentals of Infrastructure as a Service (IaaS), focusing on cloud server provisioning, Linux system administration, secure remote access, and application deployment.

The objective is to establish a functional cloud environment capable of hosting and running a Java application built with Gradle.

## Tech Stack

| Technology | Purpose |
|---|---|
| DigitalOcean | Cloud infrastructure and virtual server hosting |
| Ubuntu Linux | Server operating system |
| SSH | Secure remote server access |
| Java | Application runtime |
| Gradle | Application build automation |

## Implementation Scope

- Provision and configure an Ubuntu Droplet on DigitalOcean.
- Establish remote server access using SSH.
- Create and configure a dedicated Linux user with appropriate permissions.
- Prepare the server environment for Java application deployment.
- Build and package a Java application using Gradle.
- Deploy and run the application on the cloud server.
- Verify application accessibility and runtime behaviour.

## Deployment Workflow

```text
Java Application Source
          |
          v
    Gradle Build
          |
          v
  Application Artifact
          |
          v
 DigitalOcean Droplet
          |
          v
  Linux Configuration
          |
          v
 Application Deployment
          |
          v
  Runtime Verification
```

## Technical Focus

**Cloud Infrastructure**
- Virtual server provisioning and configuration
- Cloud networking and application connectivity

**Linux Administration**
- SSH access and user management
- File permissions and server configuration
- Application process management

**Application Deployment**
- Gradle build and packaging workflow
- Java runtime configuration
- Deployment verification and troubleshooting

## Implementation Notes

Deployment commands, configuration details, troubleshooting observations, and verification results will be documented as the implementation progresses.

## Status

**In Progress**

## Project Context

Independent hands-on implementation of cloud infrastructure and application deployment fundamentals, undertaken as part of structured DevOps engineering training.
