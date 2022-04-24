# kubernetes-pgadmin
Kubernetes pgAdmin deployment

# Namespaces
devops-Namespace.yaml


## ConfigMaps
Very \!/ not secure but you can change the password on first connection
## pgAdmin ConfigMap
pgadmin-ConfigMap.yaml


# Storages
## pgAdmin PersistentVolume using NFS storage 
Change NFS server IP and path
pgadmin-PersistentVolume-nfs.yaml

## pgAdmin PersistentVolumeClaim using NFS PersistentVolume 
pgadmin-PersistentVolumeClaim-nfs.yaml


# Deployments
## pgAdmin Deployment using NFS storage
pgadmin-Deployment-nfs.yaml


# Services

## pgAdmin LoadBalancer Service
Use one of them (I use LoadBalancer with MetalLB on my private cluster)
pgadmin-Service-LoadBalancer.yaml

## pgAdmin NodePort Service
pgadmin-Service-NodePort.yaml
