[![Build Status](https://img.shields.io/endpoint?url=https%3A%2F%2Fstatusbadge-jx.apps.serv.run%2Fentando-k8s%2Fentando-k8s-database-service-controller)](https://github.com/entando-k8s/devops-results/tree/logs/jenkins-x/logs/entando-k8s/entando-k8s-database-service-controller/master)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=entando-k8s_entando-k8s-database-service-controller&metric=alert_status)](https://sonarcloud.io/dashboard?id=entando-k8s_entando-k8s-database-service-controller)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=entando-k8s_entando-k8s-database-service-controller&metric=coverage)](https://entando-k8s.github.io/devops-results/entando-k8s-database-service-controller/master/jacoco/index.html)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=entando-k8s_entando-k8s-database-service-controller&metric=vulnerabilities)](https://entando-k8s.github.io/devops-results/entando-k8s-database-service-controller/master/dependency-check-report.html)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=entando-k8s_entando-k8s-database-service-controller&metric=code_smells)](https://sonarcloud.io/dashboard?id=entando-k8s_entando-k8s-database-service-controller)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=entando-k8s_entando-k8s-database-service-controller&metric=security_rating)](https://sonarcloud.io/dashboard?id=entando-k8s_entando-k8s-database-service-controller)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=entando-k8s_entando-k8s-database-service-controller&metric=sqale_index)](https://sonarcloud.io/dashboard?id=entando-k8s_entando-k8s-database-service-controller)


# Entando Kubernetes Keycloak Controller

This project produces the Entando Database Service Controller image. It is a run-to-completion style image
that processes a single EntandoDatabaseService custom resource and deploys the specified database service as specified.

# How to build

```
mvn clean package -Pjvm
docker build . -f Dockerfile.jvm -t {image}
```

# Further info

For more information on how to configure this image, please consult the documentation in the [entando-k8s-operator-common](https://github.com/entando-k8s/entando-k8s-operator-common) project
