# crabot

Crabot est le robot qui assiste les crapauds fous sur https://coa.crapaud-fou.org

```
cp ./bin/export.defaults ./bin/export
# edit config vars

source ./bin/export
./bin/hubot -l . # for local tests

# sync
rsync -av . dev@crap2:crabot/
# then go ssh to relaunch the bot

```

Plugins
--------
- https://github.com/shokai/hubot-rss-reader

Botmaster
---------
- ask mose if he's around
