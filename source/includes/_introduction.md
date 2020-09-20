# Introduction

This is where the documentation for all of the digital processes used by UQMC lives.

 - Website [https://uqmc.org/](https://uqmc.org/) (COMING SOON)
 - Exec Portal [https://exec.uqmc.org/](https://admin.uqmc.org/) (COMING SOON)
 - Documentation [https://uqmc.github.io/docs/](https://uqmc.github.io/docs/)

For information on how to use club website(s), go to the '[Executive Usage](https://uqmc.github.io/docs/#executive-usage)' section.

## Editing this documentation

This documentation's source code is found in the [uqmc/docs](https://github.com/uqmc/docs/) repository. The repository is a fork of [Slate](https://github.com/slatedocs/slate/). To edit its content, simply clone our 'docs' repository and edit the markdown files under `source/`. The `index.html.md` file includes the front-matter for the markdown. Within the index file it defines which other markdown files are included. These other files are located in `source/includes` and are appended to the main markdown file in the same order they are defined in, in the 'includes' array within the front-matter.

The [Slate wiki](https://github.com/slatedocs/slate/wiki) has heaps of resources on how to customise the documentation.

> Installing doc deployment dependencies

```bash
$ gem install bundler
$ bundle install
```

> Deploying docs

```bash
$ git add .
$ git commit -m "Make changes"
$ git push
$ bash ./deploy.sh
```

In order to deploy your changes to production, simply run the commands on the right. First make sure changes are in the `main` branch, then use the `deploy.sh` file to push changes over to the `gh-pages` branch where the live website looks for its content. You must have the requisite dependencies installed (Ruby, bundler, and dependencies).

## Who to talk to about club tech

_Details about who to talk to for help with website, accounts, payment stuff._
