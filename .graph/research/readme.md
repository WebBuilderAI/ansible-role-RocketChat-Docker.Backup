sch: https://www.google.com/search?q=docker+backup+volume

# relation: Article:
https://www.hava.io/blog/cattle-vs-pets-devops-explained

# discuss:
https://www.reddit.com/r/docker/comments/qotavh/how_do_you_backup_your_docker_volumes/

## quote:
https://www.reddit.com/r/docker/comments/qotavh/comment/hjpp6bk/
>I use bind mounts instead of volumes
>
>but its not that much different, just that in bind mount setup everything relevant to a container is in ~/docker/container/
>
>instead of ~/docker/container/ and /var/lib/docker/volumes
>
>anyway
>
>borg backup daily the relevant folders, that allows that restore can be just replace the entire folder from backup
>
>additionally can have script that backups database and files, and then you manually have to import them in to fresh instance
>
>Here you can check how bitwarden and bookstacks are setup for backups and restore
