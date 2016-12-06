# PokédexTracker Ghost Theme

[Ghost](https://ghost.org/) Theme for the [PokédexTracker Blog](https://pokedextracker.com/blog/)

## Development

### First-time Setup

When you clone this repo for the first time, and you intend of making changes, there are a few things you need to do before you get started (you only have to do this the very first time):

1. Make sure you are using Node v4.6.2 ([Ghost recommends `>= 4.2 < 5.*`](http://support.ghost.org/supported-node-versions/) at the time of writing). If you have [`nvm`](https://github.com/creationix/nvm), this means running `nvm install 4.6.2`.
2. Get everything setup correctly by running `npm run setup` (**WARNING: This takes a considerable amount of time**).
3. Run `npm start` to start Ghost, navigate to [`http://localhost:2368/ghost/`](http://localhost:2368/ghost/), and setup your blog (e.g. create an account, name your blog, etc).
4. Go to [`http://localhost:2368/ghost/settings/general/`](http://localhost:2368/ghost/settings/general/), scroll to the bottom, and activate the `pokedextracker` theme.

### Running

To test the theme as you make changes, just run `npm start` to start the Ghost in development mode. This will allow you to make changes and refresh to see them. Some caveats to keep in mind as you're developing:

- Ghost caches styles pretty aggressively from what I can tell, so if you aren't seeing your style changes, you'll need to do a hard refresh (<kbd>Shift</kbd>+<kbd>Cmd</kbd>+<kbd>R</kbd> on Chrome on Mac).
- Ghost only watches files that existed at startup, so if you add a new file or directory, you'll have to restart the server.

## Deployment

This theme is meant to be deployed as a bundled zip file. More details to come once I've figured it out...
