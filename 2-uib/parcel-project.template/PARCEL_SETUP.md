# Parcel

## Prerequisites

### Setup

```bash
# install Node Package Manager (npm)
apt install npm

# install Node Version Manager (nvm)
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.2/install.sh | bash
#activate the fresh installation
. ~/.bashrc

# install latest "Long Term Support" version of "node"
nvm install --lts
nvm list

# install yarn (it is faster than npm)
npm install -g yarn

```

### Warning:
DO NOT INSTALL ANY `yarn`-RELATED PACKAGE FROM YOUR DISTRIBUTIONS STANDARD REPOS!
E. G. **NO** `apt install cmdtest` AND **NO** `apt install yarn`!

Those would install a _different_ commandline tool with the same name, resulting in conflicts.

--- 

## New Project

```bash
# create project directory
mkdir NEW_PROJECT_DIR

# change to that directory
cd NEW_PROJECT_DIR

# init project to be a "node" project - this will create a `package.json`
yarn init

# add `parcel` as a "devDependency"
yarn add --dev parcel

# add script section in `package.json`


```

## In case you cloned a Project-Repository with a `package.json`
```bash
# change into the project directory
cd PROJECT_DIR

# install the dependencies configured in the `package.json`
yarn install

```

Since the `package.json` defines the dependencies, now every prerequisite should now be installed. And the scripts as defined in the `scripts`-section should also work.

Often a `dev`-script is available. Which is used during development of the software and could be run with: `yarn dev`
