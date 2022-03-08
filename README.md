# TwithGameList

This is a list of all game from Twitch API (at the last commit date). 

It contain the game

- id
- name
- box_art_url.

This come from the following endpoint ``https://api.twitch.tv/helix/games``

I've put csv file with comma (,) and semicolon (;), JSON and a mysqldump to use with mariadb (mysql should be ok too).

Unfortunately the ids are not all used because of removed item. Fortunately enough it seems like Twitch don't reuse id so I will be able to update the list pretty easily.

Edit 2022: I automated the process, it should be updated every sunday around midnight CET.
