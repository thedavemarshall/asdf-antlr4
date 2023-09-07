# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test antlr4 https://github.com/thedavemarshall/asdf-antlr4.git "java org.antlr.v4.Tool"
```

Tests are automatically run in GitHub Actions on push and PR.
