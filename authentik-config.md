# Authentik Config

## Provider
* **Type**: `OAuth2/OpenID Provider`
* **Provider Name**: `overleaf`
* **Authorization flow**: `default-provider-authorization-explicit-consent`
* **Redirect URIs/Origins**: `https://<overleaf-host>/oidc/login/callback`
* **Logout URI**: `https://<overleaf-host>/oidc/logout/callback`

## Application
* **Name**: `overleaf`
* **Slug**: `overleaf`
* **Provider**: `overleaf`
