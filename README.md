# Clipora
Deploy: push to GitHub, import the repo in Vercel (no build settings needed).

Vercel > Settings > Environment Variables:
- ADMIN_USER, ADMIN_PASS: your admin login
- ADMIN_SECRET: any long random string
- (optional, for stats) UPSTASH_REDIS_REST_URL and UPSTASH_REDIS_REST_TOKEN from a free Upstash Redis database

Admin panel: https://YOUR-SITE.vercel.app/control-room-x7k2
To change the secret path, rename control-room-x7k2.html and update vercel.json and robots.txt.
