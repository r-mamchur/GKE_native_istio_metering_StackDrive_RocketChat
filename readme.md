# GKE - native Istio and metering - integrate to StackDriver.

Terraform v0.14.3   
GKE 1.16.15-gke.4901   

 How is GKE and its Istio and Metering integrating with [ __Google Cloud's operations suite (formerly Stackdriver)__ ](https://cloud.google.com/products/operations) - Monitoring, Logging, Trace and Debugger.   



```sh
istioctl analyze
Warning [IST0002] (CustomResourceDefinition clusterrbacconfigs.rbac.istio.io) Deprecated: Custom resource type rbac.istio.io ClusterRbacConfig is removed
Warning [IST0002] (CustomResourceDefinition rbacconfigs.rbac.istio.io) Deprecated: Custom resource type rbac.istio.io RbacConfig is removed
Warning [IST0002] (CustomResourceDefinition servicerolebindings.rbac.istio.io) Deprecated: Custom resource type rbac.istio.io ServiceRoleBinding is removed
Warning [IST0002] (CustomResourceDefinition serviceroles.rbac.istio.io) Deprecated: Custom resource type rbac.istio.io ServiceRole is removed
```

