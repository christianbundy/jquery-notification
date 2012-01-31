# jQuery Notification: A simple notifications plugin

_Copyright 2011 Cory LaViska for A Beautiful Site, LLC. (http://abeautifulsite.net/)_

_Dual licensed under the MIT / GPLv2 licenses_


## Usage
	
### With default settings

	$.notification('This is a notification!');

### With custom settings

	$.notification('This is a notification!', {
		className: 'jquery-notification',
		duration: 2000,
		freezeOnHover: false,
		hideSpeed: 250,
		position: 'center',
		showSpeed: 250,
		zIndex: 99999
	});

All possible options are shown with their defaults.


## Demo

http://labs.abeautifulsite.dev/jquery-notification/