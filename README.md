# heroku-redirect
Redirects traffic from an app on Heroku to another URL

```
heroku config:add NEW_BASE_URL=http://newhost.com
```

```
heroku config:add REDIRECT_STATUS=301
```

```
git push heroku master -f
```
