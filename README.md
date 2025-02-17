# ACSONE deploy-tools

A container image with useful tools to automate deployments.

- [bash](https://linux.die.net/man/1/bash)
- [python3](https://www.python.org/doc/), >=3.8, when bash is not enough
- [curl](https://linux.die.net/man/1/curl)
- [envsubst](https://linux.die.net/man/1/envsubst)
- [helm](https://helm.sh/)
- [kubectl](https://kubernetes.io/docs/reference/kubectl/overview/)
- [kustomize](https://kubectl.docs.kubernetes.io/references/kustomize/)
- [rsync](https://linux.die.net/man/1/rsync)
- openssh-client: [ssh](https://linux.die.net/man/1/ssh),
  [ssh-agent](https://linux.die.net/man/1/ssh-agent),
  [sftp](https://linux.die.net/man/1/sftp), ... with strict host key checking
  disabled by default
- gnupg: [gpg](https://linux.die.net/man/1/gpg), ...
- [salt-ssh](https://docs.saltproject.io/en/latest/topics/ssh/)
- [git](https://git-scm.com/)
- [zip](https://linux.die.net/man/1/zip)
- [unzip](https://linux.die.net/man/1/unzip)
- [jq](https://stedolan.github.io/jq/)
- postgresql-client: https://www.postgresql.org/docs/current/reference-client.html
- [pg_activity](https://pypi.org/project/pg-activity)
- [htpasswd](https://httpd.apache.org/docs/current/programs/htpasswd.html)
- [unison](https://github.com/bcpierce00/unison)
- [rclone](https://rclone.org)

It is based on Ubuntu 22.04, but don't rely on it and if you do, be
extra sure to pin a tag.

It starts as user 0.
