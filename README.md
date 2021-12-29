<p align="center">
<img src="https://github.com/Kavee2476/KAVEE-v1/blob/v1/settings/haruka.jpg" alt="HARUKA BOT" width="200"/>

<p align="center">
    <a href="https:/github.io">
        <img
            src="https://readme-typing-svg.herokuapp.com?size=15&width=280&lines=Thanks+for+using+KAVEE+bot+�"
            alt=""
        />
    </a>
</p>




# Instalasi
## Heroku Buildpack

Click the deploy icon below !

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/zeeoneofc/Haruka)

```bash
 > heroku/nodejs
 > https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest
 > https://github.com/clhuang/heroku-buildpack-webp-binaries.git
```

## Termux
```bash
> apt update && apt upgrade
> pkg install libweb nodejs git ffmpeg
> git clone https://github.com/zeeoneofc/Haruka.git
> cd Haruka
> npm install
> node haruka.js
```

## settings
You can edit owner and other in `'./settings/config.json'`

```ts
{
	"ownername":"KAVEEOFC",
	"ownernumber":"94775792013",
	"botname":"Kavee-Bot",
	"thumbnail":"./settings/haruka.jpg",
	"session_name":"./session.json"
}
```
