Navigate into the Discourse  install directory: `cd /var/discourse`

Update source: `git pull`

Rebuild the containers (will cause some brief downtime): `./launcher stop web_only && ./launcher rebuild data && ./launcher rebuild web_only`
