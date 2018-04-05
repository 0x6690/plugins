pubnub.plugin.js
=========

This is a datasource plugin to connect freeboard.io dashboards to PubNub channels.


Installation
--------------

1. Place the file ```/datasources/pubnub.plugin.js``` in  yours freeboard.io plugins folder (```freeboard-master/js/freeboard/plugins```).

2. Edit your freeboard.io main HTML file and add the plugin to the header:

```js
<script type="text/javascript">
	head.js(
			...
			"js/freeboard/plugins/pubnub.plugin.js",
```
