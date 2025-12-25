## PlayBox – GameHub Microservices Platform

PlayBox – GameHub is a modular gaming platform built using a microservices architecture.
It demonstrates end-to-end software engineering across application development, containerization, orchestration, automation, and deployment.

## Overview

The platform allows lightweight browser-based games to run as independent services, packaged with Docker and orchestrated using Kubernetes.
Each service can scale, deploy, and update without affecting others showcasing loose coupling, service isolation, and horizontal scalability.

## Architecture (High-Level)
Application Layer:	Individual game services (e.g., Snake) + Gateway/API
Container Tier:	Docker images packaged per service
Orchestration Layer:	Kubernetes deployments, services, and ingress
Deployment Automation:	CI/CD pipeline structure using GitHub Actions & Docker Hub

## Acknowledgements

This project was developed as part of a workshop on Microservices, Docker, Kubernetes, and CI/CD automation conducted by Teju Bagalad.
I would like to thank her for providing the foundational material, guidance, and the original starter repository used as the base for this project.
