# IDMX 11ty Sass Starter

The set of development scripts in this starter is configured to watch and compile a simple Sass structure using 11ty.

The code is located in the `src` folder and the page is created in the `public` folder.

The `settings.json` in the `.vscode` folder sets the `LiveServer` configuration to serve from the `public` folder and can be used to serve the built page.

The build process includes minifiying and autoprefixing of styles via the `postbuild` script, which runs automatically after a `build`.

## Installation

**`npm install`**

>Run this command once to install the needed node modules.

## Development Scripts

**`npm start`**

> This script runs 11ty with hot reload and served at the url localhost:8080. It will reload whenever there are HTML or Sass changes.

**`npm run build`**

> This script does a production build and includes minified, autoprefixed CSS.

Use this as the "Publish command" if needed by hosting services such as Netlify.

## Resources

<small>The starter was inspired by [11ty Sass Skeleton](https://github.com/5t3ph/11ty-sass-skeleton) by [@5t3ph](https://twitter.com/5t3ph)</small>

favicon photo
https://www.freepik.com/free-psd/fruits-composition-isolated_360529439.htm#fromView=search&page=1&position=28&uuid=e97baf55-0ac4-49de-8159-78f758930939

soup photo
https://unsplash.com/photos/two-sauces-topped-with-seeds-w6ftFbPCs9I?utm_content=creditShareLink&utm_medium=referral&utm_source=unsplash

ingredients photo (border)
https://www.freepik.com/free-vector/realistic-dishes-colorful-template-with-frame-text-knife-forks-spatula-wooden-spoon-cups-pan-teapot-plates-salt-pepper-shakers-napkins_12909341.htm#fromView=search&page=1&position=28&uuid=63221bb2-01b1-4035-ac7a-6252f277d8a4

ingredients photo (pot)
https://www.freepik.com/free-photo/assorted-fresh-vegetables-falling-into-bowl_6641166.htm#fromView=search&page=1&position=20&uuid=63221bb2-01b1-4035-ac7a-6252f277d8a4

recipe content
https://www.isabeleats.com/roasted-butternut-squash-soup-with-toasted-pumpkin-seeds/