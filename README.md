# DevOps Capstone Project

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Python 3.9](https://img.shields.io/badge/Python-3.9-green.svg)](https://shields.io/)
[![Build Status](https://github.com/SahilKhaire2006/devops-capstone-project/actions/workflows/ci-build.yaml/badge.svg)](https://github.com/SahilKhaire2006/devops-capstone-project/actions)

This repository contains the DevOps Capstone Project for the IBM DevOps and Software Engineering Professional Certificate course. The project implements a Customer Accounts microservice with full CI/CD pipeline, security features, containerization, and Kubernetes deployment.

## Project Overview

A RESTful Customer Accounts microservice built with Flask, PostgreSQL, Docker, Kubernetes, and CI/CD automation using GitHub Actions and Tekton pipelines.

## Usage

```bash
source bin/setup.sh
```

## Data Model

| Name | Type | Optional |
|------|------|----------|
| id | Integer | False |
| name | String(64) | False |
| email | String(64) | False |
| address | String(256) | False |
| phone_number | String(32) | True |
| date_joined | Date | False |

## Author

Sahil Khaire

## License

Licensed under the Apache License. See [LICENSE](LICENSE)
