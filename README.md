# Wordpress Helm chart
---
This repository contains the Helm chart of a simple wordpress website (To be hosted on a K8s cluster).

##### Website URL (Hosted on GCP):
http://35.226.25.147


### Useful commands: 

- To install the Helm chart on a Kubernetes cluster: 
    ```
    >> helm install wordpress wordpress/
    ```
- To list all installed Helm charts: 
    ```
    >> helm list
    ```
- To delete the `wordpress` helm chart (Delete all installed kubernetes objects defined in the chart)
    ```
    >> helm uninstall wordpress
    ```
 