## HOW TO

1. Clone this repo.

2. Use [ASF config generator](https://justarchinet.github.io/ASF-WebConfigGenerator/) to generate your bot config (say `bot.json`).

3. Put `bot.json` into `./config`.

4. Run docker compose:
    
    ```shell
    docker compose up -d
    ```
---
> [!NOTE]
> System proxy env will be used. Change the proxy line in `docker_compose.yml` or `docker_start.sh` if you intend to custom a proxy.
