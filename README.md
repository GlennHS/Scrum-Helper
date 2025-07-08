# Scrum Helper

### Note: This repository is now archived as it was an internal project for an old company and no longer has purpose

---

A web-based application to ease daily task status updates while ensuring
that output is automatically formatted in a standardised manner.

This application boasts a keyboard-driven workflow to make usage as fast 
as possible while supporting multiple themes to suit your preference, as well as a dyslexia friendly font.

### Developing

This application uses [NodeJS](https://nodejs.org/en/) based tooling to
assist build tasks. Ensure you have a modern version installed and accessible via
command line. Before anything, run:

```shell
npm install
```

This will install any packages required for development. Once done, you'll
be able to use the following actions:

```shell
# Compile the SASS source files to their CSS output 
npm run build

# As above but watch the source files & automatically build upon change
npm run watch

# Serve the site locally for development
npm run serve
```

#### Styles

Styles within this project use [Sass](https://sass-lang.com/) and the SCSS format
in particular. Any changes to styles should only be via files in the `assets/scss/`
folder and the above commands should be used to automatically generate the complied
output to `assets/css/`.
