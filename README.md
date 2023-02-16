# Simple nginx webserver Deployment manifest

## Yaml file to deploy simple web-page (web-server) to cluster

- index.html was added as configmap (editable, using initContainer)
- using own Docker image prebuilded (locally) and pushed to DockerHub
- changes in index.html - placed line with host $HOSTNAME variable
- was used in ArgoCD
