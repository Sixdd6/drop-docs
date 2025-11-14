# Exposing your instance
Exposing your instance allows it to be accessible across your network or over the internet.

## Setting `EXTERNAL_URL`
Drop uses the `EXTERNAL_URL` environment variable for creating invitation links, OIDC redirects, and everything else. It should include the protocol, ip/domain, and port (if applicable). Examples include:
- `http://192.168.0.100:3000`
- `https://drop.my.domain/`
- `http://drop.home.arpa:3000`

## LAN
The `compose.yaml` provided in the [Quickstart guide](./quickstart.md) already exposes the Drop instance on port 3000. If you're on the same LAN as your Drop instance, you can find it's IP and then use:
```
http://[instance IP]:3000
```

as the connection URL when setting up your Drop client.

## Reverse Proxy
There is no special configuration required to run Drop behind a reverse proxy.

If you are unsure how to set up a reverse proxy, there are great guides available on YouTube, try searching for "setting up nginx proxy manager" for a guide.

## VPN
Connecting to your Drop instance via a VPN can be achieved in many ways. The simplest is to use a VPN service that comes with its own client, these often encrypt all traffic to secure your connection.

These are some of the most commonly recommended:
- Private Internet Access
- Mulvad

We offer no official support for setting up any vpn service.
