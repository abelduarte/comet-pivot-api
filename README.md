# Comet Pivot API

Anonymous-first leaderboard API for Comet Pivot.

Public route:

```text
https://abel-duarte.com/api/comet-pivot
```

VPS route target:

```caddy
handle_path /api/comet-pivot* {
  reverse_proxy 127.0.0.1:42382
}
```

Run locally:

```bash
npm test
docker compose up -d --build
curl http://127.0.0.1:42382/api/comet-pivot/health
```


<!-- Security scan triggered at 2026-08-31 16:30:58 -->

<!-- Security scan triggered at 2026-08-31 16:30:05 -->

<!-- Security scan triggered at 2026-08-31 17:44:17 -->

<!-- Security scan triggered at 2026-08-31 17:46:12 -->