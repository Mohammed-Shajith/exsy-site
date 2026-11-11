# exsy-site

The public website for **exsy**, a private UPI expense tracker for Android.

This repository exists only to host two web pages through GitHub Pages:

| Page | Address | Why it exists |
|---|---|---|
| Home page | https://mohammed-shajith.github.io/exsy-site/ | A short description of exsy. |
| Privacy policy | https://mohammed-shajith.github.io/exsy-site/privacy.html | Says what exsy reads, where the data lives, and how to delete it. |

Google requires a home page and a privacy policy web address for any app that
signs users in with Google. exsy uses Google sign-in, and its Google Cloud
project (`exsy`) points to the two addresses above.

## What is and isn't here

- Here: `index.html`, `privacy.html`, `style.css` - plain static files, no scripts, no trackers.
- Not here: the app's code. That lives in a separate, private repository.

## About exsy

exsy records UPI payments from bank SMS alerts, UPI app notifications and GPay's
payment screen, keeps them on the user's phone, and backs them up to a hidden
folder in the user's own Google Drive. It has no servers of its own.

Contact: shajithprof@gmail.com
