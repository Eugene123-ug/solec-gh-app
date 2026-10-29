# SOLEC GH web app (preview build)

This repository holds only the built web version of the SOLEC GH app, so Vercel can publish it. There is no source code and no secret here.

- Open the Vercel link on a phone and choose "Add to Home screen" to install it like an app.
- The app talks to the SOLEC GH server through the address it was built with. If the server is off, the app shows "cannot connect".
- To publish a new version: rebuild the web app, copy the new files over these, commit and push. Vercel redeploys on its own.
