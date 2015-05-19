##  Service worker vs [AppCache](http://www.html5rocks.com/en/tutorials/appcache/beginner)

* More manual work
* But much more flexibility


[Application Cache is a Douchebag](http://alistapart.com/article/application-cache-is-a-douchebag)
* Files always come from the AppCache, even if you are online
* The AppCache only updates if the content of the manifest itself chnaged
* Non-cached resources will not load on a cached page
* ...