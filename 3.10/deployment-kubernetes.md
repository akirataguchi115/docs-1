---
layout: default
description: ArangoDB Kubernetes Operator
---
# ArangoDB Kubernetes Operator

The ArangoDB Kubernetes Operator (`kube-arangodb`) is a set of operators
that you deploy in your Kubernetes cluster to:

- Manage deployments of the ArangoDB database
- Provide `PersistentVolumes` on local storage of your nodes for optimal storage performance.
- Configure ArangoDB Datacenter-to-Datacenter Replication

Each of these uses involves a different custom resource.

- Use an [`ArangoDeployment` resource](deployment-kubernetes-deployment-resource.html) to
  create an ArangoDB database deployment.
- Use an [`ArangoBackup` resource](deployment-kubernetes-backup-resource.html) to
  create an ArangoDB backup.
- Use an [`ArangoLocalStorage` resource](deployment-kubernetes-storage-resource.html) to
  provide local `PersistentVolumes` for optimal I/O performance.
- Use an [`ArangoDeploymentReplication` resource](deployment-kubernetes-deployment-replication-resource.html) to
  configure ArangoDB Datacenter-to-Datacenter Replication.

Continue with [Using the ArangoDB Kubernetes Operator](deployment-kubernetes-usage.html)
to learn how to install the ArangoDB Kubernetes operator and create
your first deployment.

For more information about the production readiness state, please refer to the
[ArangoDB Kubernetes Operator repository](https://github.com/arangodb/kube-arangodb#production-readiness-state){:target="_blank"}.