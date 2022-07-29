![Netlify Xata Plugin](./netlify-xata-plugin.png)

# Netlify Xata Plugin

The Netlify Xata Plugin enables you to sync your Xata branch with Netlify's deploy previews. If you have a pull-request with `my-feature` as the git branch name, and a `my-feature` [branch in Xata](https://docs.xata.io/concepts/branches), this plugin will point your deploy preview to the respective Xata branch. You can then review your next amazing feature with the right branch of your database!

This plugin depends on the [Xata SDK (Software Development Kit)](https://docs.xata.io/sdk/getting-started), which is easiest to get started with using the [Xata CLI (Command Line Interface)](https://docs.xata.io/cli/getting-started). Those links can help you get set up with the SDK.

## Installation

To install this Netlify build plugin, you have two options:

- You can install it via [the Netlify UI (User Interface)](https://docs.netlify.com/configure-builds/build-plugins/#ui-installation). Here, you can search for "Xata" and install the plugin.

- You can also install it using [file-based plugin installation](https://docs.netlify.com/configure-builds/build-plugins/#file-based-installation) by referencing the plugin as `netlify-plugin-xata` in your `netlify.toml`.

## Feedback?

As of right now, the only feature supported by this plugin is branch inference for deploy previews on Netlify. If you have ideas for more features that can help streamline your workflows on Netlify, please let us know by [opening an issue](issues/new). 
