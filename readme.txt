FlightSearchEngine UI - HTML, CSS, Bootstrap

To run a project:
 - Open index.html
 - Internet needed to connect to CDN

1. Assumption: a static web page, so the results are not changing dynamically, they are just coded examples; HTML5, CSS3

2. Project supports most of known browsers: Safari, Chrome, Firefox, Opera, IE (Chrome and Firefox are most chosen by users regarding browsers statistics so they shoud be supported in the first place). I would consider the last two/three versions of browsers so that for example more CSS3 properties and newer versions of jQuery were supported.


3. Responsive design - depending in the device website changes it appearance. To achieve that I used Twitter Bootstrap 3.3.0 - CSS framework.
   Project contains sample screenshots with design depending on device screen (FlightSearchEngine/screens)


4. Accessibility
   To check that there are no errors taking into account accessibility I used several tools:
		Web Accessibility Checker
		Accesssibility Toolbar in FireFox
		HiSoftware® Cynthia Says
		EvalAccess

5. W3C Markup Validation Service - successfully checked as HTML5

6. Some simple functionalities with use of jQuery (one-way/return flight tab; date picker, price slider)

7. LESS is used - CSS pre-processor
	- extends CSS with dynamic behavior such as variables, mixins, operations and functions
	- CSS is then more maintainable and extendable

Tip: While working on a local copy and checking it in Chrome one step is needed due to the security feature in chrome that disables any script that loads from file:///[path to script] from running. We need to edit the shortcut for chrome and add this switch on the end: -allow-file-access-from-files Chrome will load and run local scripts when it’s launched from this shortcut. It fixes the less.js problem and makes it actually usable for testing and debugging local sites.