##  Lifecycle - update

* The new version is installed in the background, but not yet activated. 
* It is only activated when there are no longer any pages loaded that are still using the old service worker. 
* As soon as there are no more such pages still loaded, the new service worker activates.

Source : [MDN](https://developer.mozilla.org/en-US/docs/Web/API/ServiceWorker_API/Using_Service_Workers#Updating_your_service_worker)
