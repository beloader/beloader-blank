# Blank plugin template

[![Greenkeeper badge](https://badges.greenkeeper.io/beloader/beloader-blank-plugin.svg)](https://greenkeeper.io/)

To create your own plugin, you can clone or download this template.

Then run

```
npm install
```

and start coding in src/index.js :wink:

When you're ready to publish, change `beloader_blank` in package.json
and webpack.conf/build.js (optionnaly in webpack.conf/dev.js) to your
plugin name.

Then run

```
npm run prepub
```

That will trigger build, tests and documentation.

You can then publish to NPM or configure Travis CI and semantic-release to auto-publish.
