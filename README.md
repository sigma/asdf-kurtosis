<div align="center">

# asdf-kurtosis [![Build](https://github.com/ethereum-optimism/asdf-kurtosis/actions/workflows/build.yml/badge.svg)](https://github.com/sigma/asdf-kurtosis/actions/workflows/build.yml) [![Lint](https://github.com/sigma/asdf-kurtosis/actions/workflows/lint.yml/badge.svg)](https://github.com/sigma/asdf-kurtosis/actions/workflows/lint.yml)

[kurtosis](https://docs.kurtosis.com/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add kurtosis
# or
asdf plugin add kurtosis https://github.com/ethereum-optimism/asdf-kurtosis.git
```

kurtosis:

```shell
# Show all installable versions
asdf list-all kurtosis

# Install specific version
asdf install kurtosis latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kurtosis latest

# Now kurtosis commands are available
kurtosis version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

# License

All other files within this repository are licensed under the [MIT License](https://github.com/ethereum-optimism/asdf-kurtosis/blob/main/LICENSE) unless stated otherwise.