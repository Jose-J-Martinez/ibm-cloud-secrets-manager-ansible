# Overview

IBM Cloud Secrets Manager is an SaaS offering that enables customer and internal IBM teams to can create, rotate, update, and centrally manage secrets. The secrets can be used by internal services provided by IBM Cloud itself, such as One compliance toolchains, or built-in applications (NG Fabric playbooks). All the customer accounts can have a dedicated instance. The instance is built on open-source HashiCorp Vault, which means that the [Hashicorp Vault API](https://cloud.ibm.com/docs/secrets-manager?topic=secrets-manager-vault-api) is enabled to consume and manage the lifecycle of the secrets.

## Tested with Ansible

* 2.9
* 2.10
* 2.11
* 2.12

## Python Requirements

Currently this playbook has been tested support and test against Python versions:
* 3.6
* 3.7
* 3.8

## Requirements

* IBM Cloud API key: In order to use this playbok you must have a valid  IBM Cloud API keys for services. These keys can also be stored, rotated, revoked, or even leased if you only want to provide temporary access for other team members or services. IBM Cloud API keys, in combination with the right identity and access management (IAM) policy, enable access to cloud object storage, continuous delivery and other platform services.

![IBM Cloud API Key](image.png)

## More information

- [IBM Cloud secrets manager doc](https://cloud.ibm.com/docs/secrets-manager?topic=secrets-manager-what-is-secret&interface=ui)   
- [Vault API Reference](https://cloud.ibm.com/docs/secrets-manager?topic=secrets-manager-vault-api#vault-api-login)   

## Licensing

GNU General Public License v3.0 or later.

See [LICENSE](https://www.gnu.org/licenses/gpl-3.0.txt) to see the full text.
