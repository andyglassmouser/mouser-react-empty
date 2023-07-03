# Empty React
This is an empty React package that uses Typescript and a basic dev web server so you can learn and play with React.

## Prerequisite - PNPM
There are 3 main package managers we could use. NPM, YARM, and PNPM.  This uses PNPM due to:

**Speed & disk efficiency:** pnpm is faster and more disk space efficient than the other two.

**Security:** pnpm and yarn both use checksums, pnpm also verifies the integrity of its code before executing it.

### Installation
This only needs to be done once.
- Make sure node is installed, to do this run the command prompt command `npm -v`, if you get an error or a version < 9 then install node from its website.
- Install pnpm globally run the command prompt command `npm install pnpm -g`

## Using this Package
Follow the following steps to get started.  Hot reloading should work for most changes (updates appear without the need to stop and restart the dev web server)
- Open a terminal window to the package location.
- run the command `pnpm install` to install the node modules.
- run the npm script `start` to run the dev server and see react in action.
  - You can enable the npm scripts explorer accordion on the left-hand side to quickly run these scripts, otherwise run the following command: `npm run start`.
- To stop the dev web server press `ctrl-c` in the terminal window.
