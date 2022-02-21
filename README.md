<div align="center">

# asdf-furyctl [![Build](https://github.com/sighupio/asdf-furyctl/actions/workflows/build.yml/badge.svg)](https://github.com/sighupio/asdf-furyctl/actions/workflows/build.yml) [![Lint](https://github.com/sighupio/asdf-furyctl/actions/workflows/lint.yml/badge.svg)](https://github.com/sighupio/asdf-furyctl/actions/workflows/lint.yml)


[furyctl](https://github.com/sighupio/furyctl/blob/master/README.md) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add furyctl
# or
asdf plugin add furyctl https://github.com/sighupio/asdf-furyctl.git
```

furyctl:

```shell
# Show all installable versions
asdf list-all furyctl

# Install specific version
asdf install furyctl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global furyctl latest

# Now furyctl commands are available
furyctl version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/sighupio/asdf-furyctl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [SIGHUP](https://github.com/sighupio/)
