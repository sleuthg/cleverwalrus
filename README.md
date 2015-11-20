# Clever Walrus
Clever walrus is a tongue and cheek online platform built just for the fun of it.

## Why?
I've built this platform for a few reasons:

 * Practice
 * Fun
 * A good (M)EAN skeleton for future projects.
 
## Skeleton App
Express gives us a nice little skeleton app to use.
 
```
npm install -g express-generator
express <yourappname>
```
 
However, I find that it has some idiosyncrasies that I always change. 
I'm also focusing on using MongoDB and Angular to build with the full MEAN stack, so I've included a few of those 
things as well.  (MongoDB isn't in this app quite yet).

## Heroku
I deploy my projects using Heroku.  This is mostly because that's what I started with, so it's the thing I know. Here
are a few useful commands.  And I deploy via connecting Heroku with GitHub.

### Login
```
heroku login
```

### Adding the remote 
You only need to do this once. For example `<git URL>` is `cleverwalrus` for this repo.
```
heroku git:remote -a <git URL>
```

### Pushing to Heroku
```
git push heroku master
```

### Setting the custom domain
Log in to your Heroku account, go to your app and then go to the Settings tab.  The current default domain will be
`<yourapp>.herokuapp.com`.  If you have a custom domain that you would like to use (e.g. www.cleverwalrus.com) then you
can `Add domain` here.

In my case, I'm using Pop.co as my domain server, so I had to go there, turn off `Simple Page` and activate the Heroku
third party service to point to the `cleverwalrus` subdomain (only use the subdomain name, because Pop.co knows to
append it with herokuapp.com. 
