# Customer Portal markup to build the MFEs for Space and Power

I'm using Nunjucks to build HTML pages.
The files produced in the dist folder are for preview in the browser.

Use the files in the _src folder to refer to the markup, please ignore the parts using Nunjucks (usually start with '{%').
I put some comments to indicate the parts that require translations, content from Episerver and data to inject.

## Customer Portal shell
The HTML markup is in:
* _src/html/customer-portal-shell.html

The LESS sources are in:
* _src/styles/common
* _src/styles/customer-portal-shell

All partials are imported in:
* _src/styles/customer-portal-shell.less

## Space and Power order form
The HTML markup is in:
* _src/html/space-and-power.html

The LESS sources are in:
* _src/styles/common
* _src/styles/space-and-power

All partials are imported in:
* _src/styles/space-and-power.less

## Install the project
`npm install`

## Preview in browser
`npm run serve`

## Build the project
`npm run buid`

### Build the HTML pages only
`npm run build:html`

### Build the styles only
`npm run build:css`

### Copy assets
This will copy the images and the fonts.

`npm run copy:assets`

### Clean the dist folder
`npm run clean`