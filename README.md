# docker-pihole

Docker service definitions for pihole dns.

You have to create a file `.env` in this directory containg one statement:

```
WEBPASSWORD=mySecretPassword
DNS_MASQ_LINES=address=/myserver.domain.com/192.168.0.53
```

see https://github.com/pi-hole/docker-pi-hole
