# traces.vim

This is a maintained fork of [markonm/traces.vim](https://github.com/markonm/traces.vim). Note that the plugin itself is currently considered feature-complete, so regular, major updates will not be happening unless features are suggested.

## Overview
This plugin highlights patterns and ranges for Ex commands in Command-line mode.
It also provides live preview for `:substitute`.

## Requirements
Vim 8.1 or newer

Neovim is technically supported, but keeping it supported is not a goal.

## Feature comparison
**Note**: some of the features provided by this plugin are already present in Vim/Neovim.

|                                                              | traces.vim   | Vim               |
|--------------------------------------------------------------| :----------: | :---------------: |
| `:substitute` preview                                        | ✓            |                   |
| pattern preview for `:substitute`                            | ✓            | ✓[^1]   |
| pattern preview for `:global`, `:vglobal`, `:sort`           | ✓            | ✓[^1]   |
| pattern preview for `:vimgrep`                               |              | ✓[^1]   |
| off-screen results window for `:substitute`                  | ✓            |                   |
| off-screen results window for `:global`, `:vglobal`, `:sort` | ✓            |                   |
| range preview                                                | ✓            |                   |

[1] added by patch [v8.1.0271](https://github.com/vim/vim/commit/b0acacd767a2b0618a7f3c08087708f4329580d0)

## Example
![example](img/traces_example.gif?raw=true)

## Installation
Use plugin/runtimepath manager of choice or install manually with the following command:

### Linux
`git clone --depth 1 https://github.com/lunarwatcher/traces.vim ~/.vim/pack/plugins/start/traces.vim`

### Windows
`git clone --depth 1 https://github.com/lunarwatcher/traces.vim %HOMEPATH%/vimfiles/pack/plugins/start/traces.vim`

