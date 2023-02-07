<div align="center">

# asdf-aws-sso-client [![Build](https://github.com/adamcrews/asdf-aws-sso-client/actions/workflows/build.yml/badge.svg)](https://github.com/adamcrews/asdf-aws-sso-client/actions/workflows/build.yml) [![Lint](https://github.com/adamcrews/asdf-aws-sso-client/actions/workflows/lint.yml/badge.svg)](https://github.com/adamcrews/asdf-aws-sso-client/actions/workflows/lint.yml)


[aws-sso-client](https://github.com/adamcrews/aws-sso-client) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add aws-sso-client
# or
asdf plugin add aws-sso-client https://github.com/adamcrews/asdf-aws-sso-client.git
```

aws-sso-client:

```shell
# Show all installable versions
asdf list-all aws-sso-client

# Install specific version
asdf install aws-sso-client latest

# Set a version globally (on your ~/.tool-versions file)
asdf global aws-sso-client latest

# Now aws-sso-client commands are available
aws-sso --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/adamcrews/asdf-aws-sso-client/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Adam Crews](https://github.com/adamcrews/)
