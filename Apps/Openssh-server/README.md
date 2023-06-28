# Openssh server

A sandboxed environment that allows ssh access without giving keys to the entire server. Giving ssh access via private key often means giving full access to the server. This container creates a limited and sandboxed environment that others can ssh into. The users only have access to the folders mapped and the processes running inside this container.

---

**Homepage:** https://hub.docker.com/r/linuxserver/openssh-server