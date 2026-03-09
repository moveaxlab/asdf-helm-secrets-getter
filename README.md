<div align="center">

# asdf-helm-secrets-getter [![Build](https://github.com/lucacesta/asdf-helm-secrets-getter/actions/workflows/build.yml/badge.svg)](https://github.com/lucacesta/asdf-helm-secrets-getter/actions/workflows/build.yml) [![Lint](https://github.com/lucacesta/asdf-helm-secrets-getter/actions/workflows/lint.yml/badge.svg)](https://github.com/lucacesta/asdf-helm-secrets-getter/actions/workflows/lint.yml)

[helm-secrets-getter](https://github.com/jkroepke/helm-secrets/tree/main/docs) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add helm-secrets-getter
# or
asdf plugin add helm-secrets-getter https://github.com/lucacesta/asdf-helm-secrets-getter.git
```

helm-secrets-getter:

```shell
# Show all installable versions
asdf list-all helm-secrets-getter

# Install specific version
asdf install helm-secrets-getter latest

# Set a version globally (on your ~/.tool-versions file)
asdf global helm-secrets-getter latest

# Now helm-secrets-getter commands are available
helm secrets --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/lucacesta/asdf-helm-secrets-getter/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Luca Cesta](https://github.com/lucacesta/)
