## netlify-functions-hello
### Simple test of Netlify Functions and static home page.

[![Netlify Status](https://api.netlify.com/api/v1/badges/97703bbf-2165-4e77-a19c-e703ce3f82d6/deploy-status)](https://app.netlify.com/sites/netlify-functions-hello/deploys)

---

Initial [Functions](https://docs.netlify.com/functions/overview/) test on [Netlify](https://netlify.com/). It also deploys a simple one-page index.html file as a site root.

Install yarn, then run `yarn dev` to test locally. Run `yarn post` or `npx netlify init` to create a new server instance on netlify under your account.

When you go to this resulting web page, there are 3 links to example REST API routes, implemented with a single function which can be seen in [netlify/functions/hello.js](netlify/functions/hello.js).

---

Since I have already deployed this to Netlify, you can check out the resulting site at [netlify-functions-hello.netlify.app](https://netlify-functions-hello.netlify.app/) 

To deploy this project to your own Netlify account as a starting template, click here:

[![https://www.netlify.com/img/deploy/button.svg](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/appurist/netlify-functions-hello)

