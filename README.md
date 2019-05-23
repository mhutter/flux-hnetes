# GitOps

GitOps style configuration for [flux][].

## Getting started

Well what do you think does `bootstrap.sh` do?


## Use kubeseal

To encrypt a secret using [kubeseal][]:

    kubeseal --format=yaml --cert=sealed-secrets.pub < some/secret-plain.yaml > some/secret.yaml


[flux]: https://github.com/weaveworks/flux
[kubeseal]: https://github.com/bitnami-labs/sealed-secrets#usage

---
> [Manuel Hutter](https://hutter.io/) -
> GitHub [@mhutter](https://github.com/mhutter) -
> Twitter [@dratir](https://twitter.com/dratir)
