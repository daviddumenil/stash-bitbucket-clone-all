# stash-bitbucket-clone-all
Clone all available repos from a stash/bitbucket server

## To run:
```
docker run -it --rm --name stash-bitbucket-clone-all -e STASH_URL=http://www.example.com  -e STASH_USER=myusername -e STASH_PWD=mypwd ddumenil/stash-bitbucket-clone-all
```

## To build:
```
docker build -t stash-bitbucket-clone-all .
```

Hat tip to the original script creator Jason LeMonier who chipped in on this Stack Overflow question:

https://stackoverflow.com/questions/36090075/how-to-extract-the-list-of-all-repositories-in-stash-or-bitbucket

