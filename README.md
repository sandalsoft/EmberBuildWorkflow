EmberBuildWorkflow
==================

My Emberjs build system


1) mkdir appname ; cd appname

2) yo ember.
  - no to Bootstrap-Sass [Y/n]

3) copy bower.json from below to bower.json and run bower install

5) npm install grunt-ember-templates --save-dev


8) edit index.html to incliude <script/> to new libs

`bower.json
{
  "name": "socialstalker",
  "version": "0.0.0",
  "dependencies": {
    "jquery": "~1.9.1",
    "ember": "1.0.0",
    "ember-data": "1.0.0-beta.2",
    "handlebars": "1.0.0",
    "moment": "~2.2.1",
    "ember-list-view": "~0.0.1",
    "ember-bootstrap": "~0.0.2"
  },
  "devDependencies": {
    "ember-mocha-adapter": "0.1.1"
  }
}
`

