setup
```
#install https://github.com/indexzero/http-server
npm install http-server -g

# install https://github.com/partageit/markdown-to-slides
# http://tech.graze.com/2015/07/31/easily-create-slideshow-presentations-from-markdown-with-remark-js/
npm install markdown-to-slides -g

```

ps how to draw an arrow 
https://forums.adobe.com/thread/1062749

```
# remark wiki
# https://github.com/gnab/remark/wiki/Formatting

# Main document title

## First chapter

### Chapter 1.1

Some content

### Chapter 1.2

Some content

## Second chapter

This chapter does not have sub sections

## And so on...
```

```
# https://facebook.github.io/watchman/docs/install.html
brew install watchman

# launch http-server
nohup http-server . &

# add watch man server
watchman -- trigger . rebuild '*' -- markdown-to-slides -s style.css keynote.md -o index.html

# use local js
watchman -- trigger . rebuild '*' -- sh rebuild.sh
```

