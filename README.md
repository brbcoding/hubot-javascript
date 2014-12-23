### hubot-javascript

#### Description
Packaged [javascript-sandbox](https://github.com/github/hubot-scripts/blob/master/src/scripts/javascript-sandbox.coffee) for NPM

#### Installation
`npm install --save hubot-javascript`

add `["hubot-javascript"]` to your `external-scripts.json`.

#### Examples
`hubot js [1,2,3].map(function (n) { return n * n; } )` -> `[ 1, 4, 9 ]`

`hubot run String.fromCharCode(72, 85, 66, 79, 84)` -> `'HUBOT'`

`hubot sandbox 0.1 + 0.2` -> `0.30000000000000004`