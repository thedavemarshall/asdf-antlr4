# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test antlr4 https://github.com/thedavemarshall/asdf-antlr4.git "java -jar /usr/local/lib/$ANTLR_JAR"
```

Tests are automatically run in GitHub Actions on push and PR.
