<div align="center">

# asdf-yq [![Build](https://github.com/bvaughan-nexient/asdf-yq/actions/workflows/build.yml/badge.svg)](https://github.com/bvaughan-nexient/asdf-yq/actions/workflows/build.yml) [![Lint](https://github.com/bvaughan-nexient/asdf-yq/actions/workflows/lint.yml/badge.svg)](https://github.com/bvaughan-nexient/asdf-yq/actions/workflows/lint.yml)

[yq](https://github.com/mikefarah/yq) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add yq
# or
asdf plugin add yq https://github.com/bvaughan-nexient/asdf-yq.git
```

yq:

```shell
# Show all installable versions
asdf list-all yq

# Install specific version
asdf install yq latest

# Set a version globally (on your ~/.tool-versions file)
asdf global yq latest

# Now yq commands are available
yq --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/bvaughan-nexient/asdf-yq/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ben Vaughan](https://github.com/bvaughan-nexient/)
