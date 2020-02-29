# Bitwarden Browser Extension fork by Ajay

THIS IS AN UNOFFICIAL FORK!

The fork is available in the `custom-build`(https://github.com/ajayyy/browser/tree/custom-build) branch.

This version has:

- Global edit history (instead of just passwords)
- Option to disable lock icon
- Option to lock on system lock while also locking from a timeout
- Option to lock on idle

These have been added in PRs, but have not been merged.

# Use

Make sure node.js and npm are installed.

`git clone https://github.com/ajayyy/browser`

`cd browser`

`git checkout origin/custom-build`

`git clone https://github.com/ajayyy/jslib jslib`

`git checkout origin/custom-build`

`cd ..`

`npm install`

`npm run build:dist`

The extension will be available in the `dist` folder.
