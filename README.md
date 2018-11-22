A fork of `jontewks/puppeteer-heroku-buildpack` with fonts

https://elements.heroku.com/buildpacks/jontewks/puppeteer-heroku-buildpack

# puppeteer-heroku-buildpack

Installs dependencies needed in order to run puppeteer on heroku. Be sure to include `{ args: ['--no-sandbox'] }` in your call to `puppeteer.launch`

## Usage

```sh-session
$ heroku buildpacks:set https://github.com/SaKKo/puppeteer-heroku-buildpack.git
```

### Additional language support

If you need support for Japanese, Chinese, or Korean fonts, a fork of this buildpack has been made to include those as well: https://github.com/CoffeeAndCode/puppeteer-heroku-buildpack

## Issues

If you run into any issues with this buildpack, please open an issue on this repo and/or submit a PR that resolves it. Different versions of chrome have different dependencies and so some issues can creep in without me knowing. Thanks!
