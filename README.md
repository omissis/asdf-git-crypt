<div align="center">

# asdf-git-crypt [![Build](https://github.com/omissis/asdf-git-crypt/actions/workflows/build.yml/badge.svg)](https://github.com/omissis/asdf-git-crypt/actions/workflows/build.yml) [![Lint](https://github.com/omissis/asdf-git-crypt/actions/workflows/lint.yml/badge.svg)](https://github.com/omissis/asdf-git-crypt/actions/workflows/lint.yml)

[git-crypt](https://www.agwa.name/projects/git-crypt/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add git-crypt
# or
asdf plugin add git-crypt https://github.com/omissis/asdf-git-crypt.git
```

git-crypt:

```shell
# Show all installable versions
asdf list-all git-crypt

# Install specific version
asdf install git-crypt latest

# Set a version globally (on your ~/.tool-versions file)
asdf global git-crypt latest

# Now git-crypt commands are available
git-crypt --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/omissis/asdf-git-crypt/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Claudio Beatrice](https://github.com/omissis/)
