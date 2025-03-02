# README

The examples in this chapter use StorageClasses that reference CSI plugins. Each cloud platform has its own CSI plugins with their own configuration quirks.

I've provided YAML files for LKE and GKE as follows:

|LEK version|GKE version|
|lke-pvc-test.yml|gke-pvc-test.yml|
|lke-sc-wait-keep.yml|gke-sc-wait-keep.yml|
|lke-pvc-wait-keep.yml|gke-pvc-wait-keep.yml|
|lke-app.yml|gke-app.yml|

The books always references the LKE versions. Just change to the GKE versions if your cluster is on GKE.