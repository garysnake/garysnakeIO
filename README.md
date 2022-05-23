# GarysnakeIO yeah

## Get started

This is the mind palace of the one and only Garysnake.
Well this is just my personal blog.

### How to run local server?
```
# Run Next.js in development mode
~/garysnakeIO/web
> npm run dev
```

### How to open Sanity Data control panel?
```
# Open Sanity Content Management Console
~/garysnakeIO/studio
> sanity start`
```

### Useful command from the [tutorial](https://www.sanity.io/blog/build-your-own-blog-with-sanity-and-next-js?utm_source=github&github_campaing=rbt)
```
# Install the Sanity command line interface
~/
> npm i -g @sanity/cli

# Initiate your own project in the studio folder
~/garysnakeIO/studio
> sanity init

# Add a CORS-origin rule to allow the frontend to request data
~/garysnakeIO/studio
> sanity cors add http://localhost:3000 --no-credentials

# Insert the projectId and dataset name from Sanity in client.js
~/garysnakeIO/web
> nano client.js

# Install frontend dependencies
~/garysnakeIO/web
> npm install
```


The complete setup tutrial is here:
https://www.sanity.io/blog/build-your-own-blog-with-sanity-and-next-js