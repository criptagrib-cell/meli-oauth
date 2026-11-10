# Anaya Mercado Sync (meli-oauth)

Static HTTPS pages for Mercado Libre DevCenter OAuth.

Operador: **Fabiola Martinez Anaya** (México, RFC MAAF751109IE2).

| Path | Purpose |
|------|---------|
| `/` | Landing |
| `/privacy.html` | Privacy policy |
| `/terms.html` | Terms of use |
| `/oauth/callback/` | OAuth Redirect URI (preferred) |
| `/oauth/callback.html` | Same callback, file fallback |

## DevCenter Redirect URI

Live (visibility **public**):

```text
https://meli-oauth.apps.grok.bot/oauth/callback/
```

Fallback:

```text
https://meli-oauth.apps.grok.bot/oauth/callback.html
```

Register the URL that returns **HTTP 200 without a redirect**.
