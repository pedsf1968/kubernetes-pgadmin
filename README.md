# kubernetes-pgadmin
Kubernetes pgAdmin deployment

## PersistentVolume using NFS storage 
Change NFS server IP and path
pgadmin-pv.yaml

## PersistentVolumeClaim
pgadmin-pvc.yaml

## ConfigMap for credentials 
Very \!/ not secure but you can change the password on first connection
pgadmin-configmap.yaml

# Deployment of pgAdmin
pgadmin-deployment.yaml

# Services
Use one of them (I use loadbalancer with MetalLB on my private cluster)
pgadmin-loadbalancer-service.yaml
pgadmin-nodeport-service.yaml
