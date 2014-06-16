# jekyll-foundation-sass-compass-base #
> Ready for jekyll development with foundation/sass/compass/liverload/grunt built-in.

> **NOTE:**
> The base was built up on **Windows 7**, and it should work for Mac OS X.

## What's inside? ##
* Jekyll
* Foundation 5: a responsive front-end framework like *bootstrap*
* Sass: easier to write awesome css
* Compass: more easier to write awesome css
* Grunt: compile, compress, liverload, deploy, etc
* Bower: help manage the front-end packages

## Get started ##

#### Prerequisites ####
* Ruby
* RubyGems
* Node.js
* Npm

#### Checkout the project ####
```shell
git clone https://github.com/chuyik/jekyll-foundation-sass-compass-base.git
```

#### Install the plugins ####
```shell
bundle install
```
```shell
npm install -g grunt-cli
```
```shell
npm install -g bower
```
```shell
npm install --save-dev
```
```shell
bower install
```

#### Start local server and watcher ####
* First, it will start jekyll local server
* Second, whenever scss and js file changes, it will recompile and redeploy and reload your page.
  ```shell
  grunt
  ```

* Rebuild the jekyll html with very fast speed, using [jekyll-plus](https://github.com/imathis/guard-jekyll-plus)
  ```shell
  bundle exec guard -p
  ```

## Done? ##
Open http://localhost:4000/, and if you can see the alert comes up like this, congrats.

![Screenshot](screenshot/screenshot-1.png)

