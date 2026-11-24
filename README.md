# MUSICX — Amber Edition

Music discovery with visible YouTube embeds. Favorites and history are stored locally.

Deploy using Cloudflare Workers with `npx wrangler deploy`. Set the Worker secret `YOUTUBE_API_KEY` in Cloudflare or run `npx wrangler secret put YOUTUBE_API_KEY`. Enable YouTube Data API v3 in Google Cloud. Never commit the key.

Search requires the API key. No fabricated charts or tracks. Playlist and trending are future features.
