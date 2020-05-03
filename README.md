# dockeroj-ng [![CircleCI](https://circleci.com/gh/ZJGSU-Open-Source/docker-oj.svg?style=svg)](https://circleci.com/gh/ZJGSU-Open-Source/docker-oj)

The Next Generation of GoOnlineJudge inside Docker.

[GoOnlineJudge](https://github.com/ZJGSU-ACM/GoOnlineJudge) is an ACM/ICPC online judge platform.

This project is made up of several docker images.

+ [golang](https://hub.docker.com/_/golang/)   [![](https://images.microbadger.com/badges/version/golang.svg)](https://microbadger.com/images/golang "Get your own version badge on microbadger.com") [![](https://images.microbadger.com/badges/image/golang.svg)](https://microbadger.com/images/golang "Get your own image badge on microbadger.com")

+ [mongo](https://hub.docker.com/_/mongo/)    [![](https://images.microbadger.com/badges/version/mongo.svg)](https://microbadger.com/images/mongo "Get your own version badge on microbadger.com") [![](https://images.microbadger.com/badges/image/mongo.svg)](https://microbadger.com/images/mongo "Get your own image badge on microbadger.com")

+ [goonlinejudge](https://hub.docker.com/r/clarkzjw/goonlinejudge/) [![](https://images.microbadger.com/badges/version/happier233/goonlinejudge.svg)](https://microbadger.com/images/happier233/goonlinejudge "Get your own version badge on microbadger.com")[![](https://images.microbadger.com/badges/image/happier233/goonlinejudge.svg)](https://microbadger.com/images/happier233/goonlinejudge "Get your own image badge on microbadger.com")

+ [runserver](https://hub.docker.com/r/clarkzjw/runserver/) [![](https://images.microbadger.com/badges/version/happier233/runserver.svg)](https://microbadger.com/images/happier233/runserver "Get your own version badge on microbadger.com")[![](https://images.microbadger.com/badges/image/happier233/runserver.svg)](https://microbadger.com/images/happier233/runserver "Get your own image badge on microbadger.com")

As you may know, traditional docker image have a rather big size to download. We are working on using AlpineLinux as the base image to reduce image size. Stay focused.

## Contents

+ [Prerequisites](https://github.com/ZJGSU-ACM/docker-oj#prerequisites)

+ [Quick Start](https://github.com/ZJGSU-ACM/docker-oj#quick-start)

+ [Contributions](https://github.com/ZJGSU-ACM/docker-oj#contributions)

+ [License](https://github.com/ZJGSU-ACM/docker-oj#license)

### Prerequisites

Starting from [#c6ee631](https://github.com/ZJGSU-ACM/docker-oj/commit/c6ee63176e34fc4b459320ef67ba6a096d144e09), we begin to ship docker-oj in a new way using [docker-compose](https://docs.docker.com/compose/).

Before you begin to install docker-oj, be sure you have docker and docker-compose installed. If you are not ready, [install docker](https://docs.docker.com/engine/installation/linux/ubuntulinux/) and [docker-compose](https://docs.docker.com/compose/install/) first.

### Quick Start
Remember Add Environment TZ to your timezone. For example: TZ=Asia/Shanghai
Just fire up a terminal, clone this repo, type
```bash
docker-compose up
```
and visit http://127.0.0.1:8080 on your host, and everything is done!

### Contributions

Anything is welcome, including but not limited to issues, pull-requests, and more.

### License

[GPL v2](LICENSE)
