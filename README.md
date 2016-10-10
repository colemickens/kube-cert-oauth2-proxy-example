# kube-cert-oauth2-proxy-example

## Overview

The idea is to expose a nginx reverse proxy with automatic, free SSL that automatically adds oauth2 auth on top of the `kube-system` services.

Uses these things:

* https://github.com/PalmStoneGames/kube-cert-manager
* https://github.com/kubernetes/contrib/tree/master/ingress/controllers/nginx/examples/external-auth

