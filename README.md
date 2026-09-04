# Old School Projects — Archive

A showcase page for ~30 EPITECH coursework exercises from 2016–2019 (games, C/Assembly/systems-fundamentals exercises, and math/stats/probability scripts — the source projects live in `../Old Projects/`). Every card shows a real screenshot or terminal transcript captured by actually running the project, not a mockup or a written description alone.

**Live:** [archive.odtriki.com](https://archive.odtriki.com) (alias: `old.odtriki.com`)

## Stack

Static HTML/CSS/JS, no build step. `previews/` holds the captured screenshots (JPEG) and terminal transcripts (`.txt`) referenced by each card.

## Deploy

Self-hosted via Docker (`nginx:alpine` serving the static files) behind a Cloudflare Tunnel. See `../homeserver/docker-compose.yml`.
