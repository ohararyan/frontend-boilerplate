# Boilerplate for HTML Sites

## Install

Clone the repository in to your directory and run `npm install` to include all the necessary modules.
If bower doesn't run and returns an error you will need to run `bower install` after installation to include any bower modules.
When using this for a new project. Run `rm -rf .git` to remove the current history and then re-initialize the project using `git init` to start with a fresh repo.

## Development

Run `grunt` from the commandline to watch for changes to the directory.

All template changes should be made inside `/site`.
Images should be added to `/site/assets/img`.
All JS/CSS changes should be made in `/src` and these will be moved to the `/site/assets` folder through Grunt.