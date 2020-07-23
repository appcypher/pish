# pish
A minimal fish shell prompt made of raw fish. A minor improvement over the sashimi prompt.


## Features

- Compatible with fish 3.0+
- Displays shrinked parent directory
- Git support
  - Shows clean/dirty status
  - Shows branch ahead/behind information
  - Discourages working on master branch
- Shows error exit status in red

## Installation

You can install sashimi by cloning this repository and linking the `fish_prompt.fish` file to your `~/.config/fish/functions` directory or any directory in your fish functions path.

```shell
git clone https://github.com/appcypher/pish
cd pish
ln -s fish_prompt.fish ~/.config/fish/functions/fish_prompt.fish
```

If you are using a package manager, you have the following options:

- Using [Fisher](https://github.com/jorgebucaran/fisher):
  ```shell
  fisher add appcypher/pish
  ```
- Or, if you prefer [Oh My Fish!](https://github.com/oh-my-fish/oh-my-fish):
  ```shell
  omf install pish
  ```

## Credits

This prompt was inspired by other prompts like:

- [sashimi](https://github.com/isacikgoz/sashimi)
