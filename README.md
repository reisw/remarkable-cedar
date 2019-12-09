# Archetype

This site was generated by [www.stackbit.com](https://www.stackbit.com), v0.2.80.

Archetype original README is located [here](./README.theme.md).

The content of this site is managed by Sanity.io. Visit https://remarkable-cedar-7cc43.sanity.studio/ to manage site content

# Running Your Site Locally

1. Install a full [Ruby development environment](https://jekyllrb.com/docs/installation/)

1. Install Jekyll and Bundler

        gem install jekyll bundler

1. Install dependencies from Gemfile:

        bundle install

1. get "netlify-api-key" from project menu in [Stackbit dashboard](https://app.stackbit.com/dashboard)

1. run the following command to assign this key to `STACKBIT_API_KEY` environment variable:

        export STACKBIT_API_KEY={stackbit_netlify_api_key}

1. run the following command to fetch site contents from Sanity:

        npx @stackbit/stackbit-pull --stackbit-pull-api-url=https://api.stackbit.com/pull/5de7cc433a7bea001851b882

1. [Optional] Running Sanity Studio locally: install sanity-cli `npm install -g sanity-cli` and run `sanity start` inside the `/studio` directory

1. Build the site and make it available on a local server

        bundle exec jekyll serve

1. Browse to [http://localhost:4000](http://localhost:4000)
