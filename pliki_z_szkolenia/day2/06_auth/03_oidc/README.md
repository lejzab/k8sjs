## OIDC auth
Why do we use OIDC?

```sh
kubectl oidc-login setup \
  --oidc-issuer-url=https://accounts.google.com \
  --oidc-client-id=<ID> \
  --oidc-client-secret=<SECRET>> \
  --oidc-extra-scope=email
```

Lunch Kind
```sh
kind create cluster --config ./kind.yaml --name workshop
```

Have fun...

## Useful Links

* [kubelogin](https://github.com/int128/kubelogin)
* [dex](https://dexidp.io/docs/kubernetes/)