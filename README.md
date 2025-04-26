# VomegaCerts

[![Production](https://github.com/MikeWang000000/VomegaCerts/actions/workflows/production.yml/badge.svg)](https://github.com/MikeWang000000/VomegaCerts/actions/workflows/production.yml) [![Staging](https://github.com/MikeWang000000/VomegaCerts/actions/workflows/staging.yml/badge.svg)](https://github.com/MikeWang000000/VomegaCerts/actions/workflows/staging.yml)

## Get Latest SSL Certificate for vomega.net

```bash
export CERT_PASS=******

curl 'https://certs.vomega.net/crt/vomega.net.fullchain.pem.aes' | openssl enc -d -base64 -aes-256-ctr -pbkdf2 -pass 'env:CERT_PASS' -out vomega.net.crt
```

## File List

- [vomega.net.pem.aes](/crt/vomega.net.pem.aes)
- [vomega.net.chain.pem.aes](/crt/vomega.net.chain.pem.aes)
- [vomega.net.fullchain.pem.aes](/crt/vomega.net.fullchain.pem.aes)


## Repository

[https://github.com/MikeWang000000/VomegaCerts](https://github.com/MikeWang000000/VomegaCerts)
