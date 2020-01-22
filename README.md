# Sandbox

This Sanbox is used as a playground to solve iFrame Permission Issues with Audio Permissions.

## Run

```
npm ci
npm run start
```

## Summary

Running the project will create two http-servers, listening on Port 3000 and 9000. Open the URL http://localhost:3000 in the Browser to see the Results.

A static HTML File is served, containing a static iFrame. This iFrame uses localhost:9000 as the src address.

The Server on Port 9000 (the content of the iFrame) simply holds a Button, which should ask for Microphone Permission on click.
