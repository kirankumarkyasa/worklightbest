* jQuery tap vs click, use of plugin may not work with history.back()
	* fastbutton vs jQuery tap
* Cordova memory issue when taking photos, store to device
* Accessing contacts, filter, slow
* rendering listviews, using pagebeforeshow event
* preserving state of a page/form, use jQuery plugin, avoid subpages
	* too much memory in the DOM
	* plugin to enable navigation between regular page & page with subpages, doesn't work
* Audio recording requires patch fix as of WL 5.0.5.1
	* Cordova remove file API doesn't work
* Overriding the android back button
	* WL API doesn't allow to reset back to default functionality
	* Cordova enables ability to reset back button functionality, recommended
	* need to be overridden on every pagechange (or other events that indicate a page change)
* Spinners, WL native spinner vs jQuery mobile spinner
* Backbutton in header, component
* fixed header or any navigation control, not animated in transition, if data-id is set, wont be able to dynamically modify DOM on pagebeforeshow event
* Modernizr to detect device features
support for 3D CSS transformations
detecting SVG for d3
* d3, creates flickring when used with jQuery scrollTo plugin
* use of separate CSS file for low-res devices, ie. <iPhone5
	* detecting screen dimensions, inject css files
* fixed background, so it doesn't move between screens on transition, on iOS, might see odd behaviour
* hammerjs, detecting more complex touch events
* hiding horizontal scrollbar on slide transitions
	* modifying CSS may break some pages, listviews, no scroll event
* passing data between pages
	* through url and parse with jQuery deserialize plugin
	* or store in memory and access data on pagebeforeshow event
* Repos/Versioning