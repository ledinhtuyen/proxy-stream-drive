# proxy-stream-drive
Google Drive Streaming Video

## UPDATE:
Now, Google has stopped streaming video from Google Driver by resolve reCaptcha. I can't solve this problem.

## Install:
Run command:
```
sudo apt update && apt upgrade
git clone https://github.com/tuyenldhust/proxy-stream-drive.git
cd proxy-stream-drive
npm install && sudo npm i -g pm2 && pm2 start cluster.js
```
## End point:
- Home: ip:3000
- Getlink: ip:3000/sources?fileId={drive-id}
- Embed: ip:3000/embed.html?fileId={drive-id}

## NOTE:
- Proxy stream with Google Driver Link
- Cache link 6h
- Memory leak basic
- Support iframe - getlink - encode