# Clever Walrus
Clever walrus is a tongue and cheek online platform built just for the fun of it.

## Why?
I've built this platform for a few reasons.

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

```
git push heroku master
```