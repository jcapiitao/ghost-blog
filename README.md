# Set your own blog with Ghost

Ghost is a free and open source blogging platform written in JavaScript.

## Prerequisite

What you need :
  - NPM : the JavaScript package manager installed on your local machine ; 


## Installing on Linux

[Installing Ghost on Linux](https://docs.ghost.org/v0.11/docs/installing-ghost-on-linux)

```
$ curl -L https://github.com/TryGhost/Ghost/releases/download/0.11.12/Ghost-0.11.12.zip -o ghost.zip
$ unzip -uo ghost.zip && rm ghost.zip
``` 

You now have the tree below:
```
./
../
config.example.js
content/
core/
.git/
.gitignore
Gruntfile.js
.idea/
index.js
LICENSE
npm-shrinkwrap.json
package.json
PRIVACY.md
README.md
```

Install Ghost
```
$ npm install --production

```
