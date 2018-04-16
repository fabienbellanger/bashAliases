# Liste des alias utiles

## Docker
- `alias dockercup="docker-compose up -d"`
- `alias dockerNginx="docker exec -it nginx bash"`
- `alias dockerPhp="docker exec -it php bash"`
- `alias dockerRmAll="docker rm $(docker ps -a -q) -f"`
- `alias dockerRmiAll="docker rmi $(docker images -q) -f"`

## Git
- `alias gitfs="git flow feature start"`
- `alias gitff="git flow feature finish"`
- `alias gitrs="git flow release start"`
- `alias gitrf="git flow release finish"`
- `alias gitca="git commit --amend"`
- `alias gitprod="git push && git push origin master --tags"`

## Divers
### ls
- `alias ls='ls --color=auto'`
- `alias ll='ls -lFh'`
- `alias la='ls -A'`
- `alias l='ls -CF'`

### rm
- `alias rm='rm -i'`

### grep
- `alias grep='grep --color=auto'`
- `alias fgrep='fgrep --color=auto'`
- `alias egrep='egrep --color=auto'`
