# Wordpress On Kubernetes

![](https://buddy.works/guides/thumbnails/wordpress-kubernetes-cover.png)

Deploying Wordpress in Kubernetes.

Default Base64 Passphrase is `example`.

- Create Seperate namespace.
- Create a 1GB SSD Disk for Backend.
- Create a 1GB SSD Disk for Frontend.
- Create Secret Key for Backend & Frontend.
- Create Deployment for both containers.
- Expose Both Deployments on Kubernetes Services.
- Frontend Serice can regiter on already reserved IP on Gcloud.

TODO:
- Manage Media to run Wordpress Container as Replicas.