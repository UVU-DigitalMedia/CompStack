# CompStack
This is where we build the competency definition, mapping, and storage web app.

# Requirements

* node / npm
* bower

# Install

1. Clone this repo if you don't have it already.
    `git clone https://github.com/UVU-DigitalMedia/CompStack`
2. Switch to the appropriate branch (Master has documentaion, braydons_branch has the dev version of the app).
    `git checkout braydons_branch`
3. cd to the project directory.
    `cd CompStack`
4. Run `npm install`
5. Run `bower install`
6. Run `npm start` and reload will load the app in your default browser

Any changes made to the public folder will cause the browser to reload automatically.

The app will run on port 3000 so you can access it from localhost:3000

# Dev Tools

`npm run spock` vulcanizes the project
`npm run checkapp` runs polylint on the project