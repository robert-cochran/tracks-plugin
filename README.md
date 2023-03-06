tracks-plugin

about
    
    plugin that stores youtube links to play in the background while you work
    to save the hassle of managing 10 tabs the play your favourite youtube
    tracks.
    
    this is the plugin version of /robert-cochran/tracks-nb-gh/. 

status 

    purgatory.

    to play tracks the plugin generates an html page with an embedded video at
    the top and all the stored youtube links in a list below. each link has a
    play button that loads its youtube link into the embedded video player.

    as the generated html page is not visible to the public (url will be some
    random hashed type string) this causes some youtube links with higher
    sharing restrictions to not allow videos to play on the page. an example of
    this can be seen when an embedded video will say 'cannot play video here,
    to watch, follow the link and play on youtube.com'. the same
    videos will work fine in the public implementation of the app at
    /robert-cochran/track-nb-gh/ (this uses a publically accesible github-pages
    page). not sure what headers are causing this and if i can turn them off or
    not.
    
