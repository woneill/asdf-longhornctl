<div align="center">

# asdf-longhornctl [![Build](https://github.com/woneill/asdf-longhornctl/actions/workflows/build.yml/badge.svg)](https://github.com/woneill/asdf-longhornctl/actions/workflows/build.yml) [![Lint](https://github.com/woneill/asdf-longhornctl/actions/workflows/lint.yml/badge.svg)](https://github.com/woneill/asdf-longhornctl/actions/workflows/lint.yml)

[longhornctl](https://longhorn.io/docs/latest/advanced-resources/longhornctl/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add longhornctl
# or
asdf plugin add longhornctl https://github.com/woneill/asdf-longhornctl.git
```

longhornctl:

```shell
# Show all installable versions
asdf list-all longhornctl

# Install specific version
asdf install longhornctl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global longhornctl latest

# Now longhornctl commands are available
longhornctl help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/woneill/asdf-longhornctl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Bill ONeill](https://github.com/woneill/)
