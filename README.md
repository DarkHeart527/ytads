# YouTube Adverts
## This script allows your website to show advertisements as YouTube videos. You may set view lengths, enable / disable muting, show time remaining, and more.
## Links
[Documentation](#documentation) \
[Setting Videos](#setting-videos) - [Muting - Enable / Disable](#muting) - [Controling User Interaction](#controlling-user-interaction) \
[Autoplay](#autoplay) - [Playing / Pausing](#playing-pausing)
## Need an example?
### [Click Here!](https://darkheart527.github.io/ytads/example)

# Documentation
## Settings Videos
### Settings videos is actually quite simple! When settings videos, the player only uses id's at this time. You may set a start time just by stating ',(amountOfSeconds)'. Ex: EOtpmFTpgIE,30 to start it at 30 seconds. In the near future, I will add url's, but only https, others with throw an error, remove it from the array, and try to select a new one. Not changing the id's will use my default ones.
```
ytads.videos = ['EOtpmFTpgIE', '_2ob3sKqWV0,25']
```
[Back To Top](#youtube-adverts)
