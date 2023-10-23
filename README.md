# PhilipsTaxxorStyles
This patternlab contains the HTML source blocks, styling and javascript of the Philips Resultshub website, as well as the historical sites.

In the future this should be the base for all custom output channels (Web, PDF, 20-F etc).

## Installation
Install dependancies ``` npm install```
Start patternlab ``` npm start```

Patternlab will now automatically start in your browser

## Folder structure
All changes should be made in the ```source``` folder. Patternlab will automatically copy everything to the ```public``` folder and refresh the browser.
* ```_patterns``` folder - Here you can find the Handlebars files which are used to render the HTML parts.

[Read more about the pattern structure here](https://patternlab.io/docs/pattern-organization.html)
***
* ```css``` folder - This folder contains all source files (SCSS) for the styling of the Resultshub website components

At the moment, there are 2 root files that are being compiled, style.scss and navigation.scss (navigation is temperary as this is only needed to inlcude the new header in the 'old' resultshub website)
***
* ```js``` folder - This folder contains all source files for the javascript of the Resultshub website

For now, there is only one simple js file to handle hash navigation, scrolltop etc.
***

## Using the rendered HTML

All rendered HTML can be viewed within Patternlab and is built up from small atoms towards full templates and pages.
Resulting pages can be found in the pages dropdown of the Patternlab UI.

### More information about patterns

You can find more information about the setup of the HTML / Handlebars by clicking on 'Show Pattern Info'
