This data is from my [naldaramjui](http://naldaramjui.com) Korean testing site. The site runs on [Google App Engine](https://developers.google.com/appengine/). For the longest time I couldn't get my data out of there, which was annoying. The [documentation](https://developers.google.com/appengine/docs/python/tools/uploadingdata) now notes that you have to change your app authentication method, and then you can download to a screwy sqlite format that doesn't seem to really work with the Korean unicode I have all over the place. Downloading as CSV is not a command-line option to 'appcfg.py', which would be nice, so you have to [figure out](http://nirvanatikku.tumblr.com/post/38490289648/appengine-download-csv-data) how to create and update by hand another configuration file in order to get CSVs. BUT NOW I HAVE SOME DATA! It could be fun to play with it. Feel free!
