<div align="center">

# asdf-awless [![Build](https://github.com/edr-rreilly/asdf-awless/actions/workflows/build.yml/badge.svg)](https://github.com/edr-rreilly/asdf-awless/actions/workflows/build.yml) [![Lint](https://github.com/edr-rreilly/asdf-awless/actions/workflows/lint.yml/badge.svg)](https://github.com/edr-rreilly/asdf-awless/actions/workflows/lint.yml)

[awless](https://github.com/edr-rreilly/awless) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add awless
# or
asdf plugin add awless https://github.com/edr-rreilly/asdf-awless.git
```

awless:

```shell
# Show all installable versions
asdf list-all awless

# Install specific version
asdf install awless latest

# Set a version globally (on your ~/.tool-versions file)
asdf global awless latest

# Now awless commands are available
awsless --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/edr-rreilly/asdf-awless/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Robert Reilly](https://github.com/edr-rreilly/)
