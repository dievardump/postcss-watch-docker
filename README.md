# postcss-watch-docker

PostCSS-cli not working in watch mode in docker image.

## Before start

`npm install`

## Outside docker

`npm run build` : builds `public/global.css`

`npm run dev` : builds `public/global.css` and watches for change


## Inside docker

You can set the command inside the docker-compose.yml (command that is executed at the start of the container) and then run:

`docker-compose up -d`

2 behaviors depending on the command you set:

`npm run build` : builds `public/global.css`

`npm run dev` : does not do anything and doesn't watch for changes.