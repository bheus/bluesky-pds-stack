# bluesky-pds-stack

Bluesky PDS for `pds.builtbybrendan.com`, deployed on apple-pi as a Portainer Git stack (5-minute polling). Exposed via the Cloudflare tunnel → `:2583`.

Secrets (`PDS_JWT_SECRET`, `PDS_ADMIN_PASSWORD`, `PDS_PLC_ROTATION_KEY_K256_PRIVATE_KEY_HEX`, `PDS_EMAIL_SMTP_URL`) live in the Portainer stack environment.

Dependabot proposes image bumps weekly; merging to `main` deploys.
