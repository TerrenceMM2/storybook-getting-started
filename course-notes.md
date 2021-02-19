# Pluralsight - Storybook: Getting Started - Course Notes

## 01 - Overview

## 02 - Why Use Storybook?

-   Framework agnostic
-   Runs a local development environment
-   Can quickly manage data and state

## 03 - Install Storybook

**Adding Storybook to a New Project**

1. Install JS framework (ex. React) & setup boilerplate (ex. `npx create-react-app my-app`).

2. Run `npx sb init` to add Storybook directories, setup files, and scripts.

**NOTE:** Storybook needs to be installed into a project that is already setup with a framework. It will not work on an empty project.

**Adding Storybook to an Existing Project**

Run the following command from the code repo's root folder in the terminal:

```
$ npx -p @storybook/cli sb init
```

This will create a `.storybook` and `stories` folder similar to the manual setup. Sample stories are provide and the `package.json` `storybook` script adds a specific port.
