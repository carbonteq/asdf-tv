<div align="center">

# asdf-tv [![Build](https://github.com/carbonteq/asdf-tv/actions/workflows/build.yml/badge.svg)](https://github.com/carbonteq/asdf-tv/actions/workflows/build.yml) [![Lint](https://github.com/carbonteq/asdf-tv/actions/workflows/lint.yml/badge.svg)](https://github.com/carbonteq/asdf-tv/actions/workflows/lint.yml)

[tv (tidy-viewer)](https://github.com/alexhallam/tidy-viewer) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities

# Install

Plugin:

```shell
asdf plugin add tidy-viewer

# or

asdf plugin add tidy-viewer https://github.com/carbonteq/asdf-tv.git
```

tidy-viewer:

```shell
# Show all installable versions
asdf list-all tidy-viewer

# Install specific version
asdf install tidy-viewer latest

# Set a version globally (on your ~/.tool-versions file)
asdf global tidy-viewer latest

# Now tidy-viewer commands are available
tidy-viewer --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/carbonteq/asdf-tv/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Carbonteq](https://github.com/carbonteq/)
