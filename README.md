# Heroku Buildpack for diff-pdf

Installs [diff-pdf](https://github.com/vslavik/diff-pdf) on Heroku.

* Builds from source code according to [these instructions](https://github.com/vslavik/diff-pdf#compiling-from-sources).
* Requires the dependencies described [here](https://github.com/vslavik/diff-pdf#ubuntu).
  * These can be installed using [heroku-buildpack-apt](https://elements.heroku.com/buildpacks/heroku/heroku-buildpack-apt).
