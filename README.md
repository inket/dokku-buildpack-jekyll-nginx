This is a dokku buildpack for installing Jekyll 2.5.3 with Nginx.

Tested with `dokku v0.4.2-45-ge471214` and `jekyll-2.5.3`

### Usage

Just add a `.env` file in the root of your jekyll project containing:

```
export BUILDPACK_URL=https://github.com/inket/dokku-buildpack-jekyll-nginx.git
```

### Other

For Jekyll 3.x, use [inket/dokku-buildpack-jekyll3-nginx](https://github.com/inket/dokku-buildpack-jekyll3-nginx)

### Credit

@resurge for fixing the Jekyll install process.

Fork tree:

- [shsteven/dokku-buildpack-jekyll-nginx](https://github.com/shsteven/dokku-buildpack-jekyll-nginx)

	- [nbudin/heroku-buildpack-jekyll-nginx](https://github.com/nbudin/heroku-buildpack-jekyll-nginx)

		- [mchung/heroku-buildpack-nginx](https://github.com/mchung/heroku-buildpack-nginx)