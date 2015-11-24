portify for Rdio
=======

This branch permits you to import Rdio playlists into Google Play Music All Access.

This is a modification to [portify](https://github.com/mauimauer/portify) which is detailed below. Usage of this modded version can be [found here](http://srccd.com/posts/transfer-your-rdio-playlists-to-google-play-music-all-access#showhow).

This actually will work with any service as long as you can export your playlist in the format of (1 per line):
artist - song title

I use a bookmarklet that works with Rdio playlists - [forked here](https://gist.github.com/srccd/5938636).


portify
=======

Transfers your Spotify playlists to Google Music: All Access

By using Portify you may violate both Spotify's and Google's Terms of Service. You agree that
you are using Portify on your own risk. The author does not accept liability (as far as permitted by law) for any loss arising from any use of this tool.
If you choose not to agree to these terms, then you may not use this tool.

You can read about portify here: [http://www.maui.at/2013/06/portify/](http://www.maui.at/2013/06/portify/)

License
-------

Licensed under the terms of the Apache 2.0 License
All Trademarks are the property of their respective owners.

Building portify
----------------
* Make sure you have installed a usable build enviroment (gcc, make & co.)
* Install Node.js (using your favourite package manager, but make sure it's newer than 0.8)
* Clone the git repo (master branch)
* Go into the ./data/ directory and run npm install (This will fetch and compile all depenencies of portify)
* Try running the daemon by executing node app.js in the ./data/ folder
* Open your favourite browser and go to localhost:3132

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/mauimauer/portify/trend.png)](https://bitdeli.com/free "Bitdeli Badge")
[![Analytics](https://ga-beacon.appspot.com/UA-374323-19/portify/README?pixel)](https://github.com/igrigorik/ga-beacon)
