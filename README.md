# postcss-watch-docker

PostCSS-cli not working in watch mode in docker image.

## Outside docker

`npm run build` : builds `public/global.css`

`npm run dev` : builds `public/global.css` and watches for change


## Inside docker

Now if you set the commands in the docker-compose.yml (command that is executed at the start of the container)

`npm run build` : builds `public/global.css`

`npm run dev` : does not do anything and doesn't watch for changes.