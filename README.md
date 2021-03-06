# Deploy Status
[![Netlify Status](https://api.netlify.com/api/v1/badges/238028e0-4537-4561-8107-3f98bb7d7612/deploy-status)](https://app.netlify.com/sites/nervous-mestorf-7c319e/deploys)

# Stackbit Exto Theme

This site was generated by [www.stackbit.com](https://www.stackbit.com), v0.2.80.

Stackbit Exto Theme original README is located [here](./README.theme.md).

# Running Your Site Locally

1. Install a full [Ruby development environment](https://jekyllrb.com/docs/installation/)

1. Install Jekyll and Bundler

        gem install jekyll bundler

1. Install dependencies from Gemfile:

        bundle install

1. get "stackbit-api-key" from project menu in [Stackbit dashboard](https://app.stackbit.com/dashboard)

1. run the following command to assign this key to `STACKBIT_API_KEY` environment variable:

        export STACKBIT_API_KEY={stackbit_netlify_api_key}

1. run the following command to fetch additional site contents from Stackbit if needed:

        npx @stackbit/stackbit-pull --stackbit-pull-api-url=https://api.stackbit.com/pull/5e231d948e5514001b144ce1

1. Build the site and make it available on a local server

        bundle exec jekyll serve

1. Browse to [http://localhost:4000](http://localhost:4000)
