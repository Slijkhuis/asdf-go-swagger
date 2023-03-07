<div align="center">

# asdf-go-swagger [![Build](https://github.com/Slijkhuis/asdf-go-swagger/actions/workflows/build.yml/badge.svg)](https://github.com/Slijkhuis/asdf-go-swagger/actions/workflows/build.yml) [![Lint](https://github.com/Slijkhuis/asdf-go-swagger/actions/workflows/lint.yml/badge.svg)](https://github.com/Slijkhuis/asdf-go-swagger/actions/workflows/lint.yml)


[go-swagger](https://github.com/go-swagger/go-swagger) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add go-swagger
# or
asdf plugin add go-swagger https://github.com/Slijkhuis/asdf-go-swagger.git
```

go-swagger:

```shell
# Show all installable versions
asdf list-all go-swagger

# Install specific version
asdf install go-swagger latest

# Set a version globally (on your ~/.tool-versions file)
asdf global go-swagger latest

# Now go-swagger commands are available
swagger --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/Slijkhuis/asdf-go-swagger/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Slijkhuis](https://github.com/Slijkhuis/)
