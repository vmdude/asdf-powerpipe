<div align="center">

# asdf-powerpipe [![Build](https://github.com/vmdude/asdf-powerpipe/actions/workflows/build.yml/badge.svg)](https://github.com/vmdude/asdf-powerpipe/actions/workflows/build.yml) [![Lint](https://github.com/vmdude/asdf-powerpipe/actions/workflows/lint.yml/badge.svg)](https://github.com/vmdude/asdf-powerpipe/actions/workflows/lint.yml)

[powerpipe](https://powerpipe.io/docs) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Install

Plugin:

```shell
asdf plugin add powerpipe
# or
asdf plugin add powerpipe https://github.com/vmdude/asdf-powerpipe.git
```

powerpipe:

```shell
# Show all installable versions
asdf list-all powerpipe

# Install specific version
asdf install powerpipe latest

# Set a version globally (on your ~/.tool-versions file)
asdf global powerpipe latest

# Now powerpipe commands are available
powerpipe --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/vmdude/asdf-powerpipe/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Frederic MARTIN](https://github.com/vmdude/)
