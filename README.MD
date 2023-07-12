# Install Docker

**Insert Docker Instructions**

Check container runs when you logout. If not:

```shell
loginctl enable-linger $UID
```

---

# Launch Dashy

```shell
docker compose up -d
```

```shell
docker exec -it dashy sh
```

inside docker shell:

```shell
yarn build-and-start
```
