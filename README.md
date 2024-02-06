# lepton-web

### 本地开发

0. 执行 `conda activate lepton-web` 切换环境
1. nvm install v21.6.1
2. nvm use v21.6.1
3. 安装 yarn 1.22.19，具体细节请询问 ChatGPT；
4. 执行 `yarn install && yarn dev` 即可。⚠️ 注意：此命令仅用于本地开发，不要用于部署！
5. 如果你想本地部署，请使用 `yarn install && yarn start` 命令，你可以配合 pm2 来守护进程，防止被杀死，详情询问 ChatGPT。
6. 修改 parse-streaming.ts 文件的 const fetchUrl = `http://127.0.0.1:9020/query`;