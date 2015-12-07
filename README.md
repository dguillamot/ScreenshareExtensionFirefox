# ScreenshareExtensionFirefox
A Firefox Add-on to enable screensharing on particular domains

This Add-on modifies the Firefox media.getusermedia.screensharing.allowed_domains and media.getusermedia.screensharing.enabled values in Firefox's "about:config" to support screensharing.


# Configuration

Open `install.rdf`

* line 4: modify the id attribute
* line 6: modify the name attribute
* line 10: modify the creator attribute
* line 11: modify the homepageURL attribute


Open `bootstrap.js`

* line 3-8: set all domains allowed to use this extension


Modify the two icon pngs if desired


Create the xpi file ( Firefox extension format )

* zip the extension source files (and not the folder that contains files !).
* rename your file extension.zip into extension.xpi




# Installation / Testing

After making changes and zipping the files according to the "# Configuration" section of this README,

Go to "about:addons" or select Add-ons from Firefox settings. Go to the Extensions tab, click the gear icon at the top right and select 'Install Add-on From file'. Under the 'Format' filter, select 'All Files'. Select the 'extension.xpi' zip file that was created in the "# Configuraiton" step.



# Reference / Documentation

Forked and only slightly modified from https://github.com/bistri/screensharing-extensions/tree/master/firefox-screensharing-extension

See README.md there for more documentation if needed.
