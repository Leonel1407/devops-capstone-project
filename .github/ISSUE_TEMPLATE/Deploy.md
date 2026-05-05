---

name: User Story
title: "[DEVOPS] Deploy to Kubernetes"
labels: devops,kubernetes
-------------------------

**As a** DevOps engineer
**I need** to deploy the service to Kubernetes
**So that** it is scalable and highly available

### Details and Assumptions

* Create Deployment and Service YAML
* Use container image

### Acceptance Criteria

```gherkin
Given a valid Docker image
When deployed to Kubernetes
Then the service should be accessible and running
```
