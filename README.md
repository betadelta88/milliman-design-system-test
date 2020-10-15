<h1 align="center">
  Milliman Design System
</h1>

> The Milliman Design System is an adaptation of the Carbon Design System. 
> Carbon is an open-source design system built by IBM. With the IBM Design
> Language as its foundation, the system consists of working code, design tools
> and resources, human interface guidelines, and a vibrant community of
> contributors.

## Getting started

To get started with how the design system works, check out the [Carbon Design System documentation](https://www.carbondesignsystem.com/).

## Download
Download the latest release from either [GitHub Release](https://github.com/Milliman-InnerSource/milliman-design-system/releases) or [GitHub Package](https://github.com/Milliman-InnerSource/milliman-design-system/packages) .

To programmatically download:
1. Create a Personal Access Token (Profile Settings -> Developer Settings -> Generate New Token 
- Please be sure that the 'read:packages' is a selected scope.
- Enable SSO for Milliman-Innersource
1. Add .npmrc to your package and redirect your registry:
```
//npm.pkg.github.com/:_authToken={YOUR_PERSONAL_ACCESS_TOKEN}
registry=https://npm.pkg.github.com/Milliman-InnerSource
```

1. Install package @Milliman-InnerSource/milliman-design-system and carbon-components

For more information on how to include this project in your CI/CD process, please refer to the [GitHub documentation] https://docs.github.com/en/packages/publishing-and-managing-packages/installing-a-package#installing-a-package

## Installation
The carbon design system is built using SASS technology. As part of our release process, we've provided two options to consume the Milliman theme applied to the Carbon Design System.

- Static CSS
- SCSS File 

### Static CSS files: 
1. Include the css for the desirable theme as you would for with any other css. 
1. Reference the CSS in your HTML file. You can find the CSS in 'themes/css'
1. Reference the JavaScript file in your HTML file. You find the JavaScript files in 'themes/js'

### SCSS File:
The SCSS files can be found in 'themes/scss'.
Include the following at the top of your index.scss file:
`@import '@MjordanMilliman/milliman-design-system-test/themes/scss/white/index.scss';`

### Fonts
Our design system uses two fonts, depending on the use. For code blocks, we use JetBrains Mono. For everything else, we use Open Sans, hosted by Google Fonts. To properly render the Open Sans font, please include the following in your root html file:
`<link href="https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,600;1,300;1,400;1,600&display=swap" rel="stylesheet">`

## How To Contribute

We're always looking for help on the design side and contributions to the repo.

If you're a designer, please reach out to:
- Tanya  Stockland (Tanya.Stockland@milliman.com)
- Kelsie Gosser (Kelsie.Gosser@milliman.com)

If you're a developer, please reach out to:
- Daniel Williams (Daniel.Williams@milliman.com)
- Matt Jordan (Matt.Jordan@milliman.com)
- Nikolas Ethore (Nikolas.Ethore@milliman.com)

