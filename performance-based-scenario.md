---
title: "Sample Scenario v2"
---

### Your Environment

A HashiCorp Vault cluster is provisioned as follows:

 `scenario-cluster-vault`
 
* Vault Address
: 127.0.0.1:8200
* Vault Token
: s.f7Ea3C3ojOYE0GRLzmhSG

The `approle/` path has the AppRole auth method enabled with the following properties:

* Role Name
: appy7
* Vault policy
: policy7
* Role ID
: xxxxxxxx-xxxxxxxx-xxxxxxxx-xxxxxxxxxxx

The application server is configured as follows:

`scenario-node-appserver`

* Server Address
: <IP_Address>
* Vault Agent Config File
: /etc/vault/agent7.hcl
* Sink Location
: /etc/vault/token.json

The Vault token should be stored in the sink location. The Vault binary is already in the **$PATH**.

### Instructions

You are configuring securely an application to retrieve credentials from the Vault. The Vault Agent should retrieve and automatically renew a Vault token using Auto-Auth and Token Sink.

Given the information provided above, configure the application server as follows:

1. Generate a `SecretID` in the Vault for the approle.
2. Retrieve a Vault token using the Vault Agent. 
3. Protect the Vault token using response wrapping on the Auth method.
4. Write the Vault token to the sink location.

### Important Notes

* You can validate the configuration by viewing the sink contents.
* If the Vault token does not exist, the configuration is not correct.

