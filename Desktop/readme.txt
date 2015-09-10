Changelog (Written 9/9/15):

URL: http://192.168.50.162:85/#/core/login


1) minovate/app/saam/js/geoxml3.js
       -Load position for "xhrFetcher.fetcher.open('GET', url, true);" moved to make site compatible with angular framework

2) Integration Status of the following modules
       -Planworx
	    -Pages and all form input objects have been imported 
	    -Demo Pages have been populated with dummy data
           *-Need to hookup missed demopage linked to from MudMotors page
            -Reporting Engine is working properly
	    -Functional JS
	    -Requires Implementation of Dynamic JS to fix CS
       -Inspectworx
	    -Currently displayed in Iframe
	    -Needs to be integrated at later date
       -Worxlog
	    -Currently displayed in Iframe
	    -Needs to be integrated at later date
       -SAAM
	    -Requires "Access-Control-Allow-Header: *" to be implemented in order to retrieve data from i-openapps server
	    -Functional JS
            -Requires Implementation of Dynamic JS to fix CS
	    -Disable table onload
            -Enable map onload event as opposed to onClick event tied to SAAM logo in header

3) Unfinished Pages:
        -Unique Dashboard Page (Currently utilizing FT Demo Admin Dashboard as placeholder)
	-Reports Page (Currently utilizing FT Demo Admin Dashboard as placeholder)





