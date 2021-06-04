# netlify-functions-hello
Simple test of Netlify Functions and static home page.

Initial [Functions](https://docs.netlify.com/functions/overview/) test on [Netlify](https://netlify.com/). It also deploys a simple one-page index.html file as a site root.

Install yarn, then run `yarn dev` to test locally. Run `yarn post` or `npx netlify init` to create a new server instance on netlify under your account.

When you go to this resulting web page, there are 3 links to example REST API routes, implemented with a single function which can be seen in [./netlify/hello.js](./netlify/hello.js).