# zigsim-ws server

this repository includes both the websocket server (src/index.js) as well as the example client (src/index.html).

uses [zigsim-ws](https://github.com/acrylicode/zigsim-ws)


```bash
# getting started

git clone git@github.com/jaeh/zigsim-server

cd zigsim-server
npm install

# one terminal, start websocket server that connects to zigsim-ws
npm run server

# another terminal, host the index.html file on [localhost:8000](http://localhost:8000)
npm run client

```