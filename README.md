# Bitwarden Browser Extension fork by Ajay

THIS IS AN UNOFFICIAL FORK!

This version has:

- Global edit history (instead of just passwords)
- Option to disable lock icon
- Option to lock on system lock while also locking from a timeout
- Option to lock on idle

These have been added in PRs, but have not been merged.

# Download

You can download a build version from [the releases list](https://github.com/ajayyy/browser/releases).

# Build

Make sure node.js and npm are installed.

`git clone https://github.com/ajayyy/browser`

`cd browser`

`git clone https://github.com/ajayyy/jslib`

`npm install`

`npm run build:prod`

The extension will be available in the `build` folder.
