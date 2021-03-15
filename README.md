# koe
this is just lavalink

configure `application.yml.example` and rename it.

then you can probably deploy to **fly.io** but first set the `$PORT` and `$PASSWORD` environment variables

for **railway.app** delete the line `application.yml` in `.gitignore` or delete the file entirely.
`railway up` will ignore any files in `.gitignore`.
then set `$PASSWORD`.

here's a fancy railway button!

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new?template=https%3A%2F%2Fgithub.com%2Fkotx%2Fkoe&envs=PASSWORD&PASSWORDDesc=Password+for+Lavalink)
