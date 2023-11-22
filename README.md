<div align="center">

# asdf-lab [![Build](https://github.com/particledecay/asdf-lab/actions/workflows/build.yml/badge.svg)](https://github.com/particledecay/asdf-lab/actions/workflows/build.yml) [![Lint](https://github.com/particledecay/asdf-lab/actions/workflows/lint.yml/badge.svg)](https://github.com/particledecay/asdf-lab/actions/workflows/lint.yml)

[lab](https://github.com/zaquestion/lab) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add lab
# or
asdf plugin add lab https://github.com/particledecay/asdf-lab.git
```

lab:

```shell
# Show all installable versions
asdf list-all lab

# Install specific version
asdf install lab latest

# Set a version globally (on your ~/.tool-versions file)
asdf global lab latest

# Now lab commands are available
lab --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/particledecay/asdf-lab/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Joey Espinosa](https://github.com/particledecay/)
