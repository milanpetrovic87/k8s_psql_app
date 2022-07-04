# k8s_psql_app
Application with psql client that connects to the psql database on Kubernetes cluster through secret. 

Persistence is made with PersistantVolume (HostPath) it is bound with PersistentVolumeClaim. 

Service for accessing psql server is ClusterIP type and it is exposed on port 5493.

Content of the manifest file:

Secret
PersistantVolume
PersistantVolumeClaim
PSQL deployment
Application deployment
Service for psql server
