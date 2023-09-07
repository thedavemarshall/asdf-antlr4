<div align="center">

# asdf-antlr4 [![Build](https://github.com/thedavemarshall/asdf-antlr4/actions/workflows/build.yml/badge.svg)](https://github.com/thedavemarshall/asdf-antlr4/actions/workflows/build.yml) [![Lint](https://github.com/thedavemarshall/asdf-antlr4/actions/workflows/lint.yml/badge.svg)](https://github.com/thedavemarshall/asdf-antlr4/actions/workflows/lint.yml)

[antlr4](https://www.antlr.org/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add antlr4
# or
asdf plugin add antlr4 https://github.com/thedavemarshall/asdf-antlr4.git
```

antlr4:

```shell
# Show all installable versions
asdf list-all antlr4

# Install specific version
asdf install antlr4 latest

# Set a version globally (on your ~/.tool-versions file)
asdf global antlr4 latest

# Now antlr4 commands are available
java -jar /usr/local/lib/$ANTLR_JAR
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/thedavemarshall/asdf-antlr4/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [David Marshall](https://github.com/thedavemarshall/)
