# A Next.js starter for the [JAMstack](https://jamstack.org)
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/netlify-templates/nextjs-starter-jamstack)

This is a boilerplate for using [Next.js](https://nextjs.org/) as a static site generator.

## Usage

### Getting started

To start your project, either:

1. Deploy to Netlify using the button above, or
2. Clone this repository and run:

```bash
npm install
```

This will take some time and will install all packages necessary to run the starter.

### Development

While developing your website, use:

```bash
npm start
```

Then visit http://localhost:3000/ to preview your new website. The Next.js development server will automatically reload the CSS or refresh the whole page, when stylesheets or content changes.

### Static build

To build a static version of the website inside the `/dist` folder, run:

```bash
npm run build
```

See [package.json](package.json) for all tasks.

## Basic Concepts

You can read more about building sites and apps with Next.js in their documentation here:

https://nextjs.org/docs


## Limitations

Please note that Next.js does not cater heavily to static site generation, and limitations of the system are listed in their docs:

https://nextjs.org/docs#limitation

These limitations mostly apply to server side rendering. A fully static site/app can avoid these limitations by fetching dynamic content at build time, making API calls from the client, and through [serverless functions](https://www.netlify.com/functions).

## Deploying to Netlify

The deploy to Netlify button above will create a new site and repo in one click. If you've created your repo manually, you can deploy to Netlify as follows:

- Push your clone to your own GitHub repository.
- [Create a new site on Netlify](https://app.netlify.com/start) and link the repository.

Now Netlify will build and deploy your site whenever you push to git.

## Enjoy!! 😸
