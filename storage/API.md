### API

1. Browser Support: Chrome 3.0+, FF 3.0+, IE 8.0+, Opera 10.5+, Safari 4.0+
2. `window.localStorage.getItem(key)`, `window.localStorage.setItem(key, value)`
3. `window.localStorage.length`, `window.localStorage.key(index)`
4. `window.removeItem(key)`, `window.clear()`
5. `window.addEventListener('storage', listener, false)`
	`e: {key, oldValue, newValue, url, storageArea}`