# [ngrok](https://ngrok.com) - secure introspectable tunnels to localhost

### "I want to expose a local server behind a NAT or firewall to the Internet."

This repository packages the ngrok agent for [snap](https://snapcraft.io/ngrok).

## Installing

```bash
sudo snap install ngrok
```

![](overview.png)

## What is ngrok?

ngrok is a reverse proxy that creates a secure tunnel from a public endpoint to a locally running web service.
ngrok captures and analyzes all traffic over the tunnel for later inspection and replay.

## What can I do with ngrok?

-   Expose any http service behind a NAT or firewall to the internet on a subdomain of ngrok.com.
-   Expose any tcp service behind a NAT or firewall to the internet on a random port of ngrok.com.
-   Inspect all http requests/responses that are transmitted over the tunnel.
-   Replay any request that was transmitted over the tunnel.

## What is ngrok useful for?

-   Temporarily sharing a website that is only running on your development machine.
-   Demoing an app at a hackathon without deploying.
-   Developing any services which consume webhooks (HTTP callbacks) by allowing you to replay those requests.
-   Debugging and understanding any web service by inspecting the HTTP traffic.
-   Running networked services on machines that are firewalled off from the Internet.


## Regarding: the latest release track

In the transition to the v3 ngrok agent, we split tracks into `v2` and `v3`. `v3` is the new default and hence "true" latest. The `latest` track is left on our `v2` agent for supporting legacy customers but may be deprecated in the future.
