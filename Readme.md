# Generate known_hosts

```sh
$ ssh-keyscan -t rsa github.com >> known_hosts
$ ssh-keyscan -t dsa github.com >> known_hosts
$ ssh-keygen -lf known_hosts
# compare to https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/githubs-ssh-key-fingerprints
```
