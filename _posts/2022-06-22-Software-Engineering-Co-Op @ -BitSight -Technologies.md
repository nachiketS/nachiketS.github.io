---
layout: post
---

### Highlights
- Optimized the PySpark querying mechanism and introduced an alternative NoSQL schema for HBase, resulting in faster response times and decreased dependency on costly HBase scans, thus enhancing API performance.
- Added an endpoint to Flask API adhering to the OpenAPI specification.
- Designed a mechanism to deal with specific failures in the ELT pipeline, reducing the service downtime from 24 hours to 10 minutes with no additional cloud resources or charges.
- Created a service that would check and auto-terminate redundant cloud resources saving around $200 daily.
- Redesigned the k8s deployments to use a single file using Helm to control the parameters for all resources, reducing maintenance time by 5 times.

### Skills : 
    PySpark, HBase, Python, Flask, OpenAPI, Kubernetes, Helm, Git