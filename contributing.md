# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test aws-sso-client https://github.com/adamcrews/asdf-aws-sso-client.git "aws-sso --help"
```

Tests are automatically run in GitHub Actions on push and PR.
