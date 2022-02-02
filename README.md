# Building a k3s cluster with ansible

This is the complementary repository to my Blog Post where you can find the full code I'am rambling about in the post.

# Variables file
I use a variables file to keep all the secrets out of this repository here is the stub of the variable file for you to use:

```yaml
ACME_USER_EMAIL: ""
ACME_SERVER: "https://acme-v02.api.letsencrypt.org/directory"

CF_USER_TOKEN: ""
CF_USER_EMAIL: ""

HELM_INSTALL: true

KUBECONFIG: /etc/rancher/k3s/k3s.yaml

KWATCH_ENABLED: true
KWATCH_VERSION: ""

NFS_SERVER_HOST: ""
NFS_SERVER_PATH: ""

TELEGRAM_CHATID: ""
TELEGRAM_TOKEN: ""
```
