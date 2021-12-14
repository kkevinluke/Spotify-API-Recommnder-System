# Spotify-API-Recommnder-System
This project will access your last listened songs on Spotify using its API, then it will request the user to select 5 favorite songs in that list, 
on which the API will proceed to make 50 recommendation of songs similar to them.

#Python Files
createplaylist.py is the main operation file.
spotifyclient.py hold all the methods to get the tracks, select favorite tracks, create a playlist. etc
track.py structures the output of the track display names.
playlist.py structures the output of the playlist display format.

#API and OAUTH
Sign up for spotify developer, ignore the client id. if your not making an app. 
Go to console > playlists > get playlist > get token > (select public, private and user-read-recently-played)
then copy the OAUTH and paste it in the creatplaylist.py, user id is your userid.

#Warning
The tokens expire, you will have to refresh and get new token if you see error 401
Sometimes due to spotify's internal policy changes the python clients scope can be limited,
this can sometime be bypassed if you have a subscription to spotify. 
But I recommend check with the community on social media to resolve any conflicts you face, 
as I myself have had many problems solved by users on stackoverflow, github etc.

All the Best.
