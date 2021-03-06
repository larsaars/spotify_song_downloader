# Spotify song downloader

Downloads songs from Spotify playlist as audio from YouTube.

## usage

```
usage: downloader.py [-h] [-p PLAYLIST] [-o OUTPUTDIR] [-c CODEC] [-r RETRIES]

optional arguments:
  -h, --help            show this help message and exit
  -p PLAYLIST, --playlist PLAYLIST
                        ID of a Spotify playlist
  -o OUTPUTDIR, --outputdir OUTPUTDIR
                        folder in which the songs will be saved into
  -c CODEC, --codec CODEC
                        preferred audio codec
  -r RETRIES, --retries RETRIES
                        retry n times on download error

```

## required packages

install with `pip install -r requirements.txt`

- `youtube-dl`
- `spotipy`
- `youtube-search-python`

## other requirements

Also, you have to create a Spotify Developer account and [register an spotify application](https://developer.spotify.com/dashboard/applications), of which you must store in a file `spotify_secrets.txt` the client id (line one) and the client secret (line two).
Don't forget to add `http://localhost:8888/callback` as redirection link in the Spotify App options.

## DISCLAIMER

I [THE AUTHOR] am not responsible for any illegal act commit with this this code.
