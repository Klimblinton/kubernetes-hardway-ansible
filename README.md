# kubernetes-hardway-ansible

##TODO Prerequisities: 
1. Generate encryption key
https://github.com/kelseyhightower/kubernetes-the-hard-way/blob/master/docs/06-data-encryption-keys.md and put it to a variable into roles/master/vars/main.yaml
2. Add binaries to shared/files/binaries folder
3. Add inventory. Add instructions to write own inventory
4. Add etcd server addresses
5. Add public ip (api gateway addr)
6. Add CIDR's (pod CIDR and cluster CIDR)
7. ==Add tags to all tasks==
8. Add Etcd replicas howto
9. Add ssl generation howto