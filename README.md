# netlifyAtlas

Run locally with netlify dev
Functions are available at ./.netlify/functions/"name"

# Connecting to Netlify

`netlify init`

Choose: `Create & configure a new site`

Team: Choose your team name

Site name: Choose a name or `enter` for a random name

Build command: `enter` since our static site does not have a build command

Directory to deploy: It should default to what is in netlify.toml. `enter` to leave it unchanged.

Netlify functions folder: It should default to what is in netlify.toml. `enter` to leave it unchanged.

After the site is created: `netlify open --admin` to reach the admin page or `netlify open --site` to see the site in production.

# Environment Variables

This project uses the npm package `dotenv` to load environment variables locally. Once the source is deployed, it will pull the enivornment variables from Netlify.

Create a package.json with `npm init -y`

Add the dotenv package with `npm i dotenv`

Create a top-level file name `.env`

In `.env`, add key-value pairs, one on each line. For example: `NAME=ALICE`



