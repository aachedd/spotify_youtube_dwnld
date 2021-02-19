# spotify_youtube_dwnld

This is a jupyter notebook to grab songs from a spotify playlist and download it from youtube

## About

This notebook utilzes the Spotify API to get Song/Artist/Album data from a given playlist. All of the song information is saved in a dataframe, and then uses youtube-search-python to search for a youtube video for each song. It takes the video link and passes it to youtube_dl to download a local FLAC file of the song. It finally saves the song metadata from the Spotify information and moves it to the local file path specified.

## Acknowledgments

Hat tip to anyone whose code was used, including:
* https://developer.spotify.com/dashboard/
* https://developer.spotify.com/documentation/web-api/reference-beta/#endpoint-get-playlists-tracks
* https://stackoverflow.com/questions/38198071/setting-localhost-as-a-spotify-redirect-uri
* https://github.com/alexmercerind/youtube-search-python
* https://gist.github.com/ibrahimokdadov/480ad18d4ca4dad5ba348ab8d803ecaa
* https://stackoverflow.com/questions/30770155/ffprobe-or-avprobe-not-found-please-install-one
* https://stackoverflow.com/questions/46382969/youtube-dl-taking-only-first-letter-of-url
* https://github.com/BtbN/FFmpeg-Builds/releases/tag/autobuild-2021-01-13-12-57
* https://github.com/ytdl-org/youtube-dl
* https://stackoverflow.com/questions/31613409/python-select-the-first-file-in-a-directory
* https://www.geeksforgeeks.org/extract-and-add-flac-audio-metadata-using-the-mutagen-module-in-python/
* https://stackoverflow.com/questions/42231932/writing-id3-tags-using-easyid3