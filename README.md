<div align="center">

# asdf-tailpipe [![Build](https://github.com/vthiery/asdf-tailpipe/actions/workflows/build.yml/badge.svg)](https://github.com/vthiery/asdf-tailpipe/actions/workflows/build.yml) [![Lint](https://github.com/vthiery/asdf-tailpipe/actions/workflows/lint.yml/badge.svg)](https://github.com/vthiery/asdf-tailpipe/actions/workflows/lint.yml)

[tailpipe](https://tailpipe.io) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add tailpipe
# or
asdf plugin add tailpipe https://github.com/vthiery/asdf-tailpipe.git
```

tailpipe:

```shell
# Show all installable versions
asdf list-all tailpipe

# Install specific version
asdf install tailpipe latest

# Set a version globally (on your ~/.tool-versions file)
asdf global tailpipe latest

# Now tailpipe commands are available
tailpipe --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/vthiery/asdf-tailpipe/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Vincent Thiery](https://github.com/vthiery/)
