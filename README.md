# common-touch

> Use common commands across a portfolio of projects

Ensure a common feel across a portfolio of projects to easily switch between projects and environments quickly. This project attempts to do this in a rather unopinionated way, require no dependencies beyond `bash`, and play nicely with other, similar projects.

This projects draws heavily on [Scripts to Rule Them All](https://githubengineering.com/scripts-to-rule-them-all/) and [StrappyDoo](https://github.com/bkeepers/strappydoo).

## No Installation

## Usage

Add to a new or existing project with:
```
git subtree add --prefix cli git@github.com:teamgunio/common-touch master --squash
```

### Commands

 * `./cli/bootstrap` - install, update and lock all pre-requisites, languages and dependencies.
 * `./cli/build` - primary entry for running builds.
 * `./cli/console` - opens an (non-)interactive console with the environment properly configured.
 * `./cli/dashboard` - open project related dashboards, monitoring tools and other important links.
 * `./cli/deploy` - primary entry for performing deployments.
 * `./cli/ci build` - invoked by CI to run test, build containers and capture artifacts.
 * `./cli/ci deploy` - invoked by CI to deploy target branch.
 * `./cli/setup` - setup a project for the first time.
 * `./cli/start` - start the application.
 * `./cli/test` - test the application.
 * `./cli/update` - update sources, dependencies and migrations.
 
