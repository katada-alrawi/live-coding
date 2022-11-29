# README

## Announcements
- Donnerstag 13:00 "Trial Lesson" von Caglar Sahinler
- Test "UIB - Assessment I"?

---

# SCSS

## Node Project 

`package.json`

### Package Managers
- `npm` & `yarn`
- `node_modules`

### Build Tools
- [Parcel](https://parceljs.org/)
  - [Parcel - Getting Started](https://parceljs.org/getting-started/webapp/)
- [webpack](https://webpack.js.org/)
- ...

## Sass Introduction
- What is a preprocessor: Quick definition of transpilation
- Different dialects/syntaxes: SASS and SCSS
  - SCSS is a superset of CSS, => every CSS file is already a valid SCSS file (at least after renaming (`style.css`/`style.scss`)

- Installing SASS: `npm install -g sass`
- or go with `parcel` recommended (see "Setup")

- Creating input: `.scss` nesting CSS rules.
- Compare the input `.scss` with the output `.css`-file.

- Add Variables
  $VAR: VALUE;

- Further Reading:
  - Mixins
  - Operators

## Sass Variables: an introduction
- Variables concept: "A box to keep values in"

- Vanilla CSS Variables: 
  Defining in `:root { --[name]: [value] }`,
  Using with `var(--[name], [fallback])`

- Sass variables: Defining with `$[name]: [value]`, Using with `$[name]`

## Links
- [SASS](https://sass-lang.com/)
- [SASS Guide](https://sass-lang.com/guide)

---

## Setup
```bash
apt install npm

# install nvm (node version manager)
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.2/install.sh | bash
. ~/.bashrc

# install yarn (faster than npm)
sudo npm install -g yarn

nvm install --lts
nvm list

```

## Usage

In the project directory:
Execute `yarn install` to install the dependencies configured in the `package.json`.

Then you can run the software in development mode by executing `yarn dev`. - This executes the script `dev` as defined in the `package.json`.


## @Teachers: Exercises

git@github.com:DigitalCareerInstitute/UIB-framework-variables.git
