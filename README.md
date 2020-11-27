# v2ray-cloudflare-nginx
A set of configuration files for running v2ray on port 443 (Websocket) and behind CloudFlare

Make sure you have the following installed on your server:
* v2ray
* nginx
* certbot

You will also need to assign Cloudflare's nameservers to your domain, and activate the proxying.

These are the relevant config-files:

`/etc/v2ray/config.json`\
`/etc/nginx/sites-enabled/your-domain`\
`/etc/letsencrypt/renewal/your-domain.tld.conf`\
`/etc/letsencrypt/renewal-hooks/post/001-restart-nginx.sh`\
