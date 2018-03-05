# Simple Monorepo

This repository contains a number of different projects, both at the root and in directories.

It is used as a simple test fixture for monorepo and multi-language support on [Snyk.io](https://snyk.io). As such, each "project" is merely the files needed to describe dependencies.

It also contains a checked-in `node_modules` directory, as a test fixture to verify that we don't automatically add projects for stuff in `node_modules/**`
