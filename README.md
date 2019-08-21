1. Install Node.js 10+.
1. [Create a token.](https://github.com/settings/tokens/new?description=archive%20script&scopes=repo)
1. Clone this Gist.
1. From this directory, install the dependencies.

   ```sh
   npm install
   ```

1. Run the script as a dry run.

   ```sh
   ORG=... GITHUB_TOKEN=... node archive.js
   ```

1. To actually archive repositories:

   ```sh
   ORG=... GITHUB_TOKEN=... FOR_REAL=1 node archive.js
   ```

_Creative Commons Zero - public domain_
