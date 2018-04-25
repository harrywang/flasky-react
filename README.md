Try to learn React.js framework by converting Flasky from JQuery to React.js

## Setup
Install Node.js and npm with Homebrew: https://changelog.com/posts/install-node-js-with-homebrew-on-os-x

add both Python and Node in .gitignore

Initialization, and install and configure webpack and babel:

```
$ cd flasky/static
$ npm init
$ npm i webpack --save-dev
$ npm i babel-core babel-loader babel-preset-env babel-preset-react --save-dev
$ npm i react react-dom --save-dev
```

Go back to the root of the folder (`flasky-react/`) and create Python virtual env and install flask.

```
$ virtualenv -p python3 venv
$ source venv/bin/activate
$ pip3 install -r requirements.txt
```

## Run

In one terminal, run `npm run watch`, which builds the static files

In another terminal, run Flask server: `$ python flasky/server/server.py`


## References
- https://medium.com/@pixxelblog/angularjs-vs-reactjs-vs-vuejs-comparison-fd125a5ab2b0
- https://codeburst.io/creating-a-full-stack-web-application-with-python-npm-webpack-and-react-8925800503d9
