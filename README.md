# Helm chart for PostgreSQL upgrade

You'll need to have your current DB instances scaled down during the procedure. 
This chart is based on [tianon/docker-postgres-upgrade](https://github.com/tianon/docker-postgres-upgrade) containers.

## Example

helm install pgupgrade --set postgres.old=10,postgres.new=11,pvcName=my-postgres-pvc .
