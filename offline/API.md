### API

1. Browser Support
	Chrome 4.0+
	FF 3.5+
	IE 10+
	Opera 10.6+
	Safari 4.0+

2. Check for browser support: `window.applicationCache`

3. `navigator.onLine`

4. `window.addEventListener('online', function(){})` and `window.addEventListener('offline', function(){})`

5. Cache States: `UNCACHED`,`IDLE`,`CHECKING`,`DOWNLOADING`,`UPDATEREADY`,`OBSOLETE`

6. `window.applicationCache.update()`: checking for a new version of the manifest and downloading new resources if necessary

