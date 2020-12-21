# react-from-scratch

This package is published globally to @designaroni/react-from-scratch

### Commands
  - `$ yarn`
  - `$ yarn start`

### Download this kit as a stand alone app
  0. Download project from the git repo on Github `$ git clone https://github.com/Designaroni/react-from-scratch.git`
  1. Customize and modify as you see fit, repeat as neccessary for new projects.

> :warning: **WARNING! Future versions of this project will support the following:**

### this app can be installed globally as a `create-*` starter kit
  - [**see more on yarnpkg.com: yarn create ->**](https://classic.yarnpkg.com/en/docs/cli/create/)
  - [**see more on stackoverflow: how-do-you-use-yarn-create-pkg-name ->**](https://stackoverflow.com/questions/44144329/how-do-you-use-yarn-create-pkg-name)

### Creating a starter kit while in development
  0. Download project from the git repo on Github `$ git clone https://github.com/Designaroni/react-from-scratch.git`
  1. Add starter kit globally with yarn: `$ yarn global add file:/path/to/react-from-scratch`
  
> :warning: **WARNING! step 1 fails to create binaries - react-from-scratch project is missing the `bin` field of the package.json**
> [**see more on npmjs.com: #bin ->**](https://docs.npmjs.com/cli/v6/configuring-npm/package-json#bin)

  ---
  Future steps once package.json bin field is added:
  
  2. Test installing react-from-scratch starter kit using `$ yarn create` syntax: `$ yarn create react-from-scratch my-app`
  3. Test installing react-from-scratch starter kit using `$ create-*` syntax: `$ create-react-from-scratch my-app`
  4. Test starting development server: `$ yarn create react-from-scratch start`
