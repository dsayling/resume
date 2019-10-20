dockerized jsonresume
=====================

Made with http://jsonresume.org

I suggest hosting with [github pages](https://pages.github.com/) since it's easy.

* just fork this repo
* rename to username.github.io
* clone and go!

You need to [install docker](https://docs.docker.com/install/).

## want to make your own resume from JSON?

* pick your [theme](https://jsonresume.org/themes/) and edit the Dockerfile with the theme; this uses [elegant](https://github.com/mudassir0909/jsonresume-theme-elegant)
 * update the `npm` package and the `-t` flag
* fill in the resume.json
* run the `./build` script
* push to your github.io page repo


more options including publishing to their registry at http://jsonresume.org

Thanks
======
Forked from https://github.com/BretFisher/resume
