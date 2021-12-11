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


