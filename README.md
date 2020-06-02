# proxy-stream-drive
Google Drive Streaming Video Basic

Install:
1) Clone repository
2) Run:  npm install pm2 -g && cd proxy-stream-drive && npm install
3) Start pm2:  npm run pm2
5) Url default: ip:3000

End point:
- Home: ip:3000
- Getlink: ip:3000/sources?fileId={drive-id}
- Embed: ip:3000/embed.html?fileId={drive-id}

NOTE:
- Proxy stream with Google Driver Link
- Cache link 6h
- Memory leak basic
- Support iframe - getlink - encode
