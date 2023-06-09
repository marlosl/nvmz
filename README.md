# nvmz plugin

This plugin adds autocompletions for [nvm](https://github.com/nvm-sh/nvm) — a Node.js version manager. It also
automatically sources nvm, so you don't need to do it manually in your `.zshrc`.

If the node version is set in the `package.json` file, this plugin will automatically load the node version configured.

To use it, add `nvmz` to the plugins array of your zshrc file:

```zsh
plugins=(... nvmz)
```

