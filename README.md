# Ankit's Blog
My Personal Blog

Powered by Zola, Hosted on Netlify  
[![Netlify Status](https://api.netlify.com/api/v1/badges/7b543d14-06d0-4f79-bee6-cb9692860a2a/deploy-status)](https://app.netlify.com/sites/euphonious-cendol-b71f98/deploys)

## Development
1. Install Zola - [getzola.org](https://www.getzola.org/documentation/getting-started/installation/)
2. Clone repository
> git clone https://github.com/nkitan/ankit-today-blog
3. Change directory to ankit-today-blog
> cd ankit-today-blog
4. Serve Zola
> zola serve


## Deployment
1. On a server, run blog using docker
> docker run -u "$(id -u):$(id -g)" -v $PWD:/app --workdir /app -p 8080:8080 ghcr.io/getzola/zola:v0.16.0 serve --interface 0.0.0.0 --port 8080 --base-url localhost

## Special Thanks to @Wolfgang
from Wolfgang's channel on [youtube](https://www.youtube.com/c/WolfgangsChannel)
and [github](https://github.com/notthebee)

