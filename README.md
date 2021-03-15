# koe
this is just lavalink

configure `application.yml.example` and rename it.

then you can probably deploy to **fly.io** without changing anything. 

for **railway.app** you'll need to change the port to `${PORT}`

ALSO delete the line `application.yml` in `.gitignore` or delete the file entirely.
`railway up` will ignore any files in `.gitignore`.
