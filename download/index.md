---
title: Download
linkTitle: Download
---
<div class="inner-content">
<div id="download-redis">

## Redis

You can download the last Redis source files here. For additional options, see the [Redis downloads](#redis-downloads) section below.

### Stable (6.2)

Redis 6.2 includes many new commands and improvements. Redis 6.2 improves on the completeness of Redis and addresses issues that have been requested by many users frequently or for a long time. 

* [Download 6.2.6](https://download.redis.io/releases/redis-6.2.6.tar.gz)
* [Redis 6.2.6 Release Notes](https://raw.githubusercontent.com/redis/redis/6.2/00-RELEASENOTES)
* [More installation options ->](#redis-downloads)

</div>

<div id="download-redis-stack">

## Redis Stack

You can download the latest Redis Stack Server binaries here. Alternatively you can use [Docker](/docs/stack/get-started/install/docker) or your package manager for [Mac](/docs/stack/get-started/install/mac-os) or [Linux](/docs/stack/get-started/install/linux).

### Stable (6.2.0)

Redis Stack Server extends Redis with modern data models, such as Document, Graph, Time Series, and data processing engines, such as search, AI, and server side functions.

* Download Redis Stack Server 6.2.0-v0 for: [macOS x86_64](https://redismodules.s3.amazonaws.com/redis-stack/redis-stack-server-6.2.0-v1.catalina.x86_64.zip) | [macOS aarch64](https://redismodules.s3.amazonaws.com/redis-stack/redis-stack-server-6.2.0-v1.monterey.arm64.zip) | [Ubuntu xenial x86_64](https://redismodules.s3.amazonaws.com/redis-stack/redis-stack-server-6.2.0-v1.xenial.x86_64.tar.gz) | [Ubuntu bionic x86_64](https://redismodules.s3.amazonaws.com/redis-stack/redis-stack-server-6.2.0-v1.bionic.x86_64.tar.gz) | [Ubuntu focal x86_64](https://redismodules.s3.amazonaws.com/redis-stack/redis-stack-server-6.2.0-v1.focal.x86_64.tar.gz) | [Redhat/CentOS 7 x86_64](https://redismodules.s3.amazonaws.com/redis-stack/redis-stack-server-6.2.0-v1.rhel7.x86_64.tar.gz) | [Redhat/CentOS 8 x86_64](https://redismodules.s3.amazonaws.com/redis-stack/redis-stack-server-6.2.0-v1.rhel8.x86_64.tar.gz) 
* [Redis Stack 6.2.0-v0 Release Notes](https://github.com/redis-stack/redis-stack/releases/tag/6.2.0-v1)
* [More installation options ->](#redis-stack-downloads)
</div>
 
<div id="download-redis-options">
  
## Redis downloads

### Release-candidate (7.0)

Redis 7.0 includes several new user-facing features, significant performance optimizations, and many other improvements. It also includes changes that potentially break backwards compatibility with older versions. 

* [Download 7.0-rc2](https://github.com/redis/redis/archive/7.0-rc2.tar.gz)
* [7.0-rc2 Release Notes](https://raw.githubusercontent.com/redis/redis/7.0/00-RELEASENOTES)

### Unstable

This is where all the development happens. Only for hard-core hackers or for folks who need to test the latest features or performance improvements. As this is an experimental build, it's not guaranteed to be fit for production deployment.

[Download Redis Unstable Build](https://github.com/redis/redis/archive/unstable.tar.gz)

### Latest Stable

The latest stable release is always available at the fixed [https://download.redis.io/redis-stable.tar.gz](https://download.redis.io/redis-stable.tar.gz) URL along with its [SHA-256 sum](https://download.redis.io/redis-stable.tar.gz.SHA256SUM).

### Older Redis Versions

#### Redis 6.x

Redis 6.0 (GA October, 2021) introduced SSL, the new RESP3 protocol, ACLs, client side caching, diskless replicas, I/O threads, faster RDB loading, new modules APIs, and many more improvements.

See the [release notes](https://raw.githubusercontent.com/redis/redis/6.0/00-RELEASENOTES) or [download 6.0.16](https://download.redis.io/releases/redis-6.0.16.tar.gz).

#### Redis 5.x

Redis 5.0 (GA October 2018) introduced the new stream data type, sorted set blocking pop operations, LFU/LRU info in RDB, a cluster manager in redis-cli, active defragmentation V2, better HyperLogLogs, and many other improvements.

See the [release notes](https://raw.githubusercontent.com/redis/redis/5.0/00-RELEASENOTES) or [download 5.0.14](https://download.redis.io/releases/redis-5.0.14.tar.gz).

### List of all releases and hash digests

You can find a [listing of all previous Redis releases](https://download.redis.io/releases/) on the [releases page](https://download.redis.io/releases/). SHA-256 digests for these downloads are available in the [redis-hashes git repository](https://github.com/redis/redis-hashes/).

### Docker

You can download and run Docker images of Redis from DockerHub. Multiple versions are available, usually updated in a short time after a new release is available.

[Go to Redis DockerHub](https://hub.docker.com/_/redis).
</div>
</div>

<div id="download-redis-stack-options">
<div class="inner-content">

## Redis Stack downloads

### RedisInsight

RedisInsight is a powerful tool for visualizing and optimizing data in Redis or Redis Stack, making real-time application development easier and more fun than ever before.

* Download the latest RedisInsight for: [macOS x86_64](https://download.redisinsight.redis.com/latest/RedisInsight-v2-mac-x64.dmg) | [macOS aarch64](https://download.redisinsight.redis.com/latest/RedisInsight-v2-mac-arm64.dmg) | [Linux](https://download.redisinsight.redis.com/latest/RedisInsight-v2-linux-x86_64.AppImage) | [Windows](https://download.redisinsight.redis.com/latest/RedisInsight-v2-win-installer.exe)
* [RedisInsight Release Notes](https://docs.redis.com/staging/release-ri-v2.0/ri/release-notes/)
 
### Release-candidate (7.0.0)

Redis Stack 7.0 includes several new user-facing features, significant performance optimizations, and many other improvements part of Redis 7.0. It also includes changes that potentially break backwards compatibility with older versions. 

* Download Redis Stack Server 7.0.0-rc1 for: [macOS x86_64](https://redismodules.s3.amazonaws.com/redis-stack/redis-stack-server-7.0.0-rc1.catalina.x86_64.zip) | [macOS aarch64](https://redismodules.s3.amazonaws.com/redis-stack/redis-stack-server-7.0.0-rc1.monterey.arm64.zip) | [Ubuntu xenial x86_64](https://redismodules.s3.amazonaws.com/redis-stack/redis-stack-server-7.0.0-rc1.xenial.x86_64.tar.gz) | [Ubuntu bionic x86_64](https://redismodules.s3.amazonaws.com/redis-stack/redis-stack-server-7.0.0-rc1.bionic.x86_64.tar.gz) | [Ubuntu focal x86_64](https://redismodules.s3.amazonaws.com/redis-stack/redis-stack-server-7.0.0-rc1.focal.x86_64.tar.gz) | [Redhat/CentOS 7 x86_64](https://redismodules.s3.amazonaws.com/redis-stack/redis-stack-server-7.0.0-rc1.rhel7.x86_64.tar.gz) | [Redhat/CentOS 8 x86_64](https://redismodules.s3.amazonaws.com/redis-stack/redis-stack-server-7.0.0-rc1.rhel8.x86_64.tar.gz) 
* [7.0.0-rc1 Release Notes](https://github.com/redis-stack/redis-stack/releases/tag/7.0.0-rc1)

</div>
</div>