# IDMX 11ty Poem Website by David DiBenedetto

## A simple web site featuring a poem by the late Marianne Moore (1887-1972)

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

<small>
  The starter was inspired by <a href="https://github.com/5t3ph/11ty-sass-skeleton">11ty Sass Skeleton</a> by <a href="https://twitter.com/5t3ph">@5t3ph</a><br>
  Background image by Joel Filipe on <a href="https://unsplash.com">Unsplash.com</a><br>
  Featured image by <a href="https://openai.com/dall-e-2/">OpenAI Dall E 2</a>
</small>
