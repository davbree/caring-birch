# Stackbit Starter Theme

This site was generated by [www.stackbit.com](https://www.stackbit.com), v0.3.21.

The content of this site is managed by Sanity.io. Visit https://caring-birch-cac59.sanity.studio/ to manage site content

# Running Your Site Locally

1. Install [Node.js and npm](https://nodejs.org/en/)

1. Install npm dependencies:

        npm install

1. Get "netlify-api-key" from project menu in [Stackbit dashboard](https://app.stackbit.com/dashboard)

1. Run the following command to assign this key to `STACKBIT_API_KEY` environment variable:

        export STACKBIT_API_KEY={stackbit_netlify_api_key}

1. Run the following command to fetch site contents from Sanity:

        npx @stackbit/stackbit-pull --stackbit-pull-api-url=https://2fbf0c2fad8c.ngrok.io/pull/5fccac59bbb3748303bdc134

1. [Optional] Run Sanity Studio locally: install sanity-cli `npm install -g @sanity/cli`, navigate to the `/studio` directory, and run `sanity install` and `sanity start`.
You may be required to login with the Sanity CLI.

1. Start a local development server:

        npm run develop

1. Browse to [http://localhost:8000/](http://localhost:8000/)
