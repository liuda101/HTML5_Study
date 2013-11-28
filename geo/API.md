### API

1. `navigator.geolocation`
2. `navigator.geolocation.getCurrentPosition(success, error, options)`
	'success`: function(result)
		`result {
			coords: {
				latitude: 29.01231,
				longitude: 119.99861,
				accuracy: 18000, // 18000 meters
				altitude: null,
				altitudeAccuracy: null,
				heading: null, // direction, in degrees relative to true north
				speed: null // ground speed in meters per second
			}
			timestamp: 1385621563359
		}`
	`error`: function(error)
		`code`:
			0: UNKNOWN_ERROR
			1: PERMISSION_DENIED
			2: POSITION_UNAVAILABLE
			3: TIMEOUT
		`message`
	`options`:
		enableHighAccuracy: `true/false`
		timeout: 10000
		maximumAge: 1000
3. `navigator.geolocation.watchCurrentPosition(success, error)` return `watchId`
4. `navigator.geolocation.clearWatch(watchId)`