# Michigan Migrant Ministries

https://www.michiganmigrantministries.com/

## Getting started

Follow these steps to set up your development environment:

1. Install Jekyll - https://jekyllrb.com/docs/installation/
1. Clone this repository
1. Run this command to install other project dependencies:
   ```
   bundle install
   ```
1. Run this command to build and serve this site:
   ```
   jekyll serve --watch
   ```
1. Open your browser to http://localhost:4000/

Here are some useful documentation links:

* Bootstrap - https://getbootstrap.com/docs/4.1/getting-started/introduction/
* Jekyll - https://jekyllrb.com/docs/

## Deploying changes

Github automatically deployes changes to the `master` branch according to this file:
```
.github/workflows/deploy-workflow.yml
```

Github pages is configured on this repository to serve files for the `www.michiganmigrantministries.com` domain.

DNS is configured for that domain to point to Github.