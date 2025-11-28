# asdf-shader-slang

An asdf/mise plugin for the Shader Slang toolchain (slangc, slangd, slangi).

Only Shader Slang **v2024.1.27 or newer** are supported.

Older releases use a different binary layout and are **not supported** by this plugin.
They will not appear in `asdf list-all shader-slang` / `mise ls-remote shader-slang`.

```shell
asdf plugin add shader-slang https://github.com/horaguy/asdf-shader-slang
asdf set shader-slang 2025.23.1

mise plugin install shader-slang https://github.com/horaguy/asdf-shader-slang
mise use shader-slang@2025.23.1
```
