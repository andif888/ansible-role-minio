Ansible Role Minio
=========

Installes Minio binary and systemd service file.  
https://docs.min.io/docs/minio-quickstart-guide.html  
https://github.com/minio/minio-service/tree/master/linux-systemd  

Tested on Ubuntu 20.04  



Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml

- hosts: servers
  roles:
    - role: username.rolename
      minio_volumes_path: /tmp/minio
      minio_listen_port: 9000
      minio_access_key: Server-Access-Key
      minio_secret_key: Server-Secret-Key
``` 


