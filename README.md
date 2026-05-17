# Jinja Slang

Provides seamless, dual-language syntax highlighting for Jinja2 templates that generate Slang and HLSL shaders. 

## Features
By assigning the `jinja-slang` language mode to your files, this extension perfectly overlays Jinja2 control tags (`{% for %}`, `{{ variable }}`) on top of native Slang/C++ shader syntax. 

## Usage
Simply save your files with the `.slang.j2` extension. VS Code will automatically detect and apply the correct dual-highlighting rules.

## Requirements
This extension acts as a bridge and requires the following extensions to function. VS Code should install them automatically when you install this extension:
* [Jinja](https://marketplace.visualstudio.com/items?itemName=wholroyd.jinja) (`wholroyd.jinja`)
* [Slang Language Extension](https://marketplace.visualstudio.com/items?itemName=shader-slang.slang-language-extension) (`shader-slang.slang-language-extension`)

## Source
[View the repository on GitHub](https://github.com/ZainSharief/jinja-slang)