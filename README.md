# Kamal Node.js

## kamal command alias

```
alias kamal='docker run -it --rm --env-file .env.production -v "$HOME/.ssh:/root/.ssh" -v "${PWD}:/workdir" -v "${SSH_AUTH_SOCK}:/ssh-agent" -v /var/run/docker.sock:/var/run/docker.sock -e "SSH_AUTH_SOCK=/ssh-agent" ghcr.io/basecamp/kamal:latest'
```
