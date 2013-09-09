
# Anime Utilities

### Description

A collection of bookmarklets and scripts that I use to download anime
episodes that stream on <http://animefreak.tv>.

Once the episodes are downloaded, I use various shell scripts to:

* automatically keep track of which episodes I've watched
* automatically play the next episode I haven't watched yet

### Setup

* clone repo
* add repo's bin folder to your PATH
* make bookmarks out of each bookmarklet

### Overall Flow

1. Go to episode page on animefreak.tv
2. Use the bookmarklets/display-animefreak-mirrors bookmark to show file links
3. Copy a link

    $> cd /path/to/show-folder
    $> download
    $> next\_episode   ### Opens the next episode in vlc media player


### Listing which episodes haven't been watched yet

    $> unwatched_episodes



