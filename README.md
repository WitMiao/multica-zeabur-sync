# multica-zeabur-sync

定时检测 GHCR 上 `multica-backend` / `multica-web` 各自的最新 semver tag（分页拉全量，前后端独立解析），并通过 Zeabur CLI 更新 VPS 上的预构建镜像。

手动触发：Actions → **Sync Multica release to Zeabur** → Run workflow
