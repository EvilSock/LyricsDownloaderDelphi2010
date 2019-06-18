# LyricsDownloaderDelphi2010


## This project was made for my fellow South-African IT students. I remember the struggles I went through trying to do this in delphi . For this reason I have made the generous decision to make my code publicly availiable so that none of you have to go through the same pain as I did.

# You gave never seen a project more jank than this one.
Yup my program is completely reliant on the fact that azlyrics.com does not change anything about their site. 

# How does this garbage work:
I just use the twebbrowser component to navigate to azlyrics.com and then take the html being rendered in the component and save it as a textfile. The textfile is saved with the name and artist of the song so you dont have to redownload it if you search for the lyrics again. I then parse through the html looking for specific tags that contain the lyrics.

# Error checking
Absolutely nothing.

# Optimisation 
Pff nope.
