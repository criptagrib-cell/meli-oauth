# Grib Mercado Sync (meli-oauth)

Static HTTPS pages for Mercado Libre DevCenter OAuth:

| Path | Purpose |
|------|---------|
| `/` | Landing |
| `/privacy.html` | Privacy policy |
| `/terms.html` | Terms of use |
| `/oauth/callback/` | OAuth Redirect URI (preferred) |
| `/oauth/callback.html` | Same callback, file fallback |

## DevCenter Redirect URI

After Cursor Publish (visibility **public**):

```text
https://meli-oauth.cursor.app/oauth/callback/
```

If the host only serves the file form, use:

```text
https://meli-oauth.cursor.app/oauth/callback.html
```

Register the URL that returns **HTTP 200 without a redirect**.
