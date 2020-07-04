# API-RULES PLAYGROUND

## Installation

> install docker ref: https://docs.docker.com/docker-for-mac/install/
> git clone :)

## How to

> Add your rule in test.conf
> Connect to the VPN
> run in your terminal "./start"
> play:
```
  curl -X GET \
  http://localhost:8080/account/v1/release/info/payments/6910346738?caller.id=3432 \
  -H 'x-auth-token: YOUR_FURY_TOKEN'
```
> run in your terminal "./stop"
> REMEMBER to run "./start" when you change your test.conf