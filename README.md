<div align="center">

# asdf-rosa [![Build](https://github.com/mrWinston/asdf-rosa/actions/workflows/build.yml/badge.svg)](https://github.com/mrWinston/asdf-rosa/actions/workflows/build.yml) [![Lint](https://github.com/mrWinston/asdf-rosa/actions/workflows/lint.yml/badge.svg)](https://github.com/mrWinston/asdf-rosa/actions/workflows/lint.yml)


[rosa](https://access.redhat.com/products/red-hat-openshift-service-aws) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add rosa
# or
asdf plugin add rosa https://github.com/mrWinston/asdf-rosa.git
```

rosa:

```shell
# Show all installable versions
asdf list-all rosa

# Install specific version
asdf install rosa latest

# Set a version globally (on your ~/.tool-versions file)
asdf global rosa latest

# Now rosa commands are available
rosa help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mrWinston/asdf-rosa/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Marius Schulz](https://github.com/mrWinston/)
