# kubeLOL
Kubernetes Scripting. Deploy. HA


Based on Ranchers K3s : https://docs.k3s.io/installation/ha

INTRODUCTION
K3s requires two or more server nodes for this HA configuration. See the Requirements guide for minimum machine requirements.


For example, a command like the following could be used to install the K3s server with a MySQL database as the external datastore and set a token:
curl -sfL https://get.k3s.io | sh -s - server \
  --token=SECRET \
  --datastore-endpoint="mysql://username:password@tcp(hostname:3306)/database-name"
