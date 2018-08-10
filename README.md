# heroku-buildpacks-git-sha
Exports the Heroku SOURCE_VERSION variable (usually the Git SHA) to an env variable (`GIT_SHA`) that application code can access.

## Usage

`heroku buildpacks:set https://github.com/ignitionapp/heroku-buildpack-git-sha --app your-app-name`

For more information, refer to the [Heroku Buildpack](https://devcenter.heroku.com/articles/buildpacks) or [Heroku Multiple Buildpack](https://devcenter.heroku.com/articles/using-multiple-buildpacks-for-an-app) documentation.

The git sha will be available to application code via the env var `GIT_SHA`.

## License
MIT
