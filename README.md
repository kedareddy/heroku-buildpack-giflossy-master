heroku-buildpack-gifsicle-lossy
=========================

Heroku buildpack for gifsicle support.

Binary for gificle is compiled using the a release on [gifsicle's repo](https://github.com/pornel/giflossy).

Current version: 1.82.1

Usage
=====

To use, checkout the usage guide on https://github.com/ddollar/heroku-buildpack-multi then add this repo in your `.buildpacks`.

Example:

    $ cat .buildpacks
    https://github.com/heroku/heroku-buildpack-ruby
    https://github.com/kedareddy/heroku-buildpack-giflossy-master
