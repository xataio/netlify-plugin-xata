![Netlify Xata Plugin](./netlify-xata-plugin.png)

# Netlify Xata Plugin

The Netlify Xata Plugin enables to sync your xatabase branch with your Netlify's pull-request previews.

As example, if you have a pull-request with `my-feature` as git branch name and a `my-feature` branch in xata.
This plugin will take care to point the correct xata branch inside the preview. You can then review your next amazing feature with the associated xatabase!

## Installation

### Installing the client sdk

This plugin inject the git branch information into `@xata.io/client`, the easiest way to get started is to used our CLI.

https://docs.xata.io/cli/getting-started

### Installing the Netlify build plugin

You have two options:

- [The Netlify UI](https://docs.netlify.com/configure-builds/build-plugins/#ui-installation).
  Here, you can search for "Xata" and install the plugin.

- [File-based plugin installation](https://docs.netlify.com/configure-builds/build-plugins/#file-based-installation).
  You can install the plugin as `netlify-plugin-xata` in your `netlify.toml`
  file.
