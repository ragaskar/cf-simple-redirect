# Simple Redirect App

This app, when pushed to CloudFoundry, will redirect requests to the REDIRECT_URI that you specify.

Usage:

1. `git clone` this repo.
1.  Open `manifest.yml` and change the name & REDIRECT_URI. Do not include the scheme. (E.G., "google.com" vs. "https://google.com")
1. `cf push`

