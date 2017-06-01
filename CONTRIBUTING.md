# Contributing

Welcome, and thanks for your interest in contributing to the Synapse Python client!

## I don't want to read this whole thing I just have a question!!!

> **Note:** Please don't file an issue to ask a question. You'll get faster results by using the resources below.

We have an official forum and a detailed FAQ and where the community and maintainers can chime in with helpful advice if you have questions.

* [Synapse Help Forum](https://www.synapse.org/#!SynapseForum:default)
* [Synapse FAQ](http://docs.synapse.org/articles/faq.html)

## What should I know before I get started?

### Doing some work

#### Get some work to do
The open work items (bugs and new features) are tracked in JIRA .

#### Fork and clone this repository

See the [Github docs](https://help.github.com/articles/fork-a-repo/) for how to make a copy (a fork) of a repository to your own Github account.

Then, [clone the repository](https://help.github.com/articles/cloning-a-repository/) to your local machine so you can begin making changes.

#### Create a feature branch

On your local machine make sure you have the latest version of the `develop` branch:

```
git checkout develop
git pull upstream develop
```

The development life cycle is diagrammed above:
1. Pull the latest content from the `develop` branch of this central repository (not your fork).
1. Create a feature branch which off the `develop` branch.
1. After completing work and testing locally, push to your fork.
1. In Github, create a pull request from the feature branch of your fork to the develop branch of the central repository.

> *A Sage Bionetworks engineer must review and accept your pull request.*


```
git checkout -b SYNPY-1234
```

By contributing, you are agreeing that we may redistribute your work under this [license](LICENSE.md).
