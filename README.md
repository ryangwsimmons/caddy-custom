# caddy-custom
Caddy Web Server with the following plugins added:
- [caddy-dns/cloudflare](https://github.com/caddy-dns/cloudflare)
- [hslatman/caddy-crowdsec-bouncer](https://github.com/hslatman/caddy-crowdsec-bouncer)


Initial code based on [Caddy Web Server with ACME-DNS Provider](https://github.com/timelordx/caddy-dns-acmedns)

[![Docker Build and Publish](https://github.com/ryangwsimmons/caddy-custom/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/ryangwsimmons/caddy-custom/actions/workflows/docker-publish.yml)

**Docker Pull Command**

* from GitHub Container Registry: 

```
docker pull ghcr.io/ryangwsimmons/caddy-custom:latest
```

**Documentation**

* [Caddy Docker](https://hub.docker.com/_/caddy)
* [Caddy Server](https://caddyserver.com/docs/)
* [Cloudflare module for Caddy Server](https://github.com/caddy-dns/cloudflare)
* [CrowdSec Bouncer for Caddy](https://github.com/hslatman/caddy-crowdsec-bouncer)
