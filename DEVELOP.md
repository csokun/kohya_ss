# Build Docker Image

```bash
# avoid building errors cause by requirements.txt -e ./sd-scripts line
git submodule update --init

docker compose build
```
