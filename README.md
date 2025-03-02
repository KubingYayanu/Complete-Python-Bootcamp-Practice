# README

# GitHub

- [The older Python 2 Notebooks](https://github.com/jmportilla/Complete-Python-Bootcamp)
- [Python 3 Notebooks](https://github.com/Pierian-Data/Complete-Python-3-Bootcamp)

# Docker 環境建立

- 執行 Docker Compose

```bash
$ docker compose -f docker-compose.yaml -p jupyter up -d

# 重新編譯相依服務 Image
$ docker compose -f docker-compose.yaml -p jupyter up -d --build
```
