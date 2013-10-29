# NGINX Buildpack

**Note**: This has only been tested with [starphleet](https://github.com/wballard/starphleet)

## Structure
If you have a `index.html` this will static serve, put this late in your
chain of buildpacks, or explicitly set with `BUILDPACK_URL`.
* nginx.conf.erb - Optional File: overrides `conf/nginx.conf.erb`, this
  serves as a template to generate your config.
* mime.types - Optional File: overrides `conf/mime.types`

