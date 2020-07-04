munin-plugin-redis
===

Munin plugin for Redis.

# Installation

```bash
$ wget https://raw.github.com/tknrjp/munin-plugin-redis/master/redis_ -P /etc/munin/plugins
```

# Configuration

```
[redis_*]
env.redis_cli {Redis client command path (Default: redis-cli)}
env.redis_host {Host name or IP address (Default: 127.0.0.1)}
env.redis_port {Port (Default: 6379)}
env.redis_pass {Password (Default: <empty>)}
```
