
# Anime Utilities

Utilities I've written to organize and simply my anime watching experience.

### Description

A collection of bookmarklets and scripts that I use to download anime
episodes that stream on <http://animefreak.tv>.

Once the episodes are downloaded, I use various shell scripts to:

* automatically keep track of which episodes I've watched
* automatically play the next episode I haven't watched yet
* list all episodes I have yet to watch

### Setup

* clone repo
* add repo's bin folder to your PATH
* make bookmarks out of each bookmarklet

### Directory Structure

I have a root anime folder:

    ~/Desktop/Anime

In that folder, I have a folder for each show:

    ~/Desktop/Anime/Blood_Lad
    ~/Desktop/Anime/Brothers_Conflict
    ~/Desktop/Anime/Naruto
    ~/Desktop/Anime/Yosuga_no_Sora

In each show's folder, I make sure the episode numbers are the same width,
smaller numbers are padded with zeros on the left (e.g. blood-lad-1.mp4 =>
blood-lad-01.mp4):

    ~/Desktop/Anime/Blood_Lad/Blood Lad Episode 01.mp4
    ~/Desktop/Anime/Blood_Lad/Blood Lad Episode 02.mp4
    ~/Desktop/Anime/Blood_Lad/Blood Lad Episode 03.mp4
    ~/Desktop/Anime/Blood_Lad/Blood Lad Episode 04.mp4

### Overall Flow

1. Go to episode page on animefreak.tv
2. Use the bookmarklets/display-animefreak-mirrors bookmark to show file links
3. Copy a link
4. Run these commands in a shell:

````
    $> cd /path/to/show-folder
    $> download
    $> next\_episode
````


### Listing which episodes haven't been watched yet

    $> unwatched_episodes



