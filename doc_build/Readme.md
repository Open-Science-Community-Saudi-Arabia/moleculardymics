# doc_build

For now, this build system is taken from https://github.com/mwhamgenomics/nf-core-docs. Uses
[Astro](https://astro.build) to build an nf-core-styled documentation mini-site.

## Usage

Prerequisite: [nodejs](https://nodejs.org)

    $ cd doc_build
    $ npm install
    $ python bin/build.py path/to/repo gh-repo-owner gh-repo-name
    $ npm run build-cache path/to/repo

Then either of:

    $ npm run start
    $ npm run preview

Or build into a static site at `dist/`:

    $ npm run build

