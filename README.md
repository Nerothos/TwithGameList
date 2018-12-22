# TwithGameList

This is a list of all game from Twitch API (at the moment of the last commit). 

It contain the game

- id
- name
- box_art_url.

This come from the following endpoint ``https://api.twitch.tv/helix/games``

I've put csv file with comma (,) and semicolon (;) and JSON for use with the mariadb dump.

Unfortunately the ids are not all used because of removed item. Fortunately enough it seems like Twitch don't reuse id so I will be able to update the list pretty easily.

I will update my nodejs program after including the update check functions.