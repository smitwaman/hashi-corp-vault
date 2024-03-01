# hashicorp-vault
configuring hashicorp vault
Credentials management with hashicorp vault 

It has two functions as dev and prod.
Vault Server deployment becomes tricky in prod than dev. some common errors occur such as proxy server stop, ipc lock etc which causes difficulties during configuration.   
It can deploy using docker and kubernetes with deployment svc and configmap files.

You may need to set the following environment variables:
 $ export VAULT_ADDR=’http://0.0.0.0:8200’

The unseal key and root token are displayed below in case you want to

Seal/unseal the Vault or re-authenticate.

Unseal Key: EvDkt/dwS0e3SUDtCMP6QwSze+mIqVT9fvm68/zNNqk=

Root Token: hvs.GpM2srywL6YXVdhct0v6OdM8

Copy token and paste into token 

![op for vault](https://github.com/smitwaman/credmnt/blob/main/images/Screenshot%202024-03-01%20192834.png)
