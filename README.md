# yarn-konsole-completion

This plugin is the same [official](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/yarn) one, but this one runs on Konsole, the original one don't.

## Installation

### Using [Antigen](https://github.com/zsh-users/antigen)

Bundle `yarn-konsole-completion` in your `.zshrc`

```shell
antigen bundle bacali95/yarn-konsole-completion
```

### Using [zplug](https://github.com/b4b4r07/zplug)

Load `zsh-better-npm-completion` as a plugin in your `.zshrc`

```shell
zplug "bacali95/yarn-konsole-completion", nice:10

```

### Using [zgen](https://github.com/tarjoilija/zgen)

Include the load command in your `.zshrc`

```shell
zgen load bacali95/yarn-konsole-completion
```

### As an [Oh My ZSH!](https://github.com/robbyrussell/oh-my-zsh) custom plugin

Clone `yarn-konsole-completion` into your custom plugins repo

```shell
git clone https://github.com/bacali95/yarn-konsole-completion ~/.oh-my-zsh/custom/plugins/yarn-konsole-completion
```

Then load as a plugin in your `.zshrc`

```shell
plugins+=(yarn-konsole-completion)
```

### Manually

Clone this repository somewhere (`~/.yarn-konsole-completion` for example)

```shell
git clone https://github.com/bacali95/yarn-konsole-completion.git ~/.yarn-konsole-completion
```

Then source it in your `.zshrc`

```shell
source ~/.yarn-konsole-completion/yarn-konsole-completion.plugin.zsh
```

## License

MIT © Nasreddine Bac Ali
