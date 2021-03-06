# setup-resharper

This action sets up a [ReSharper Command Line Tools](https://www.jetbrains.com/help/resharper/ReSharper_Command_Line_Tools.html) environment for use in actions by:

- downloading and caching a version of ReSharper CTL and adding it to PATH

# Usage

See [action.yml](action.yml)

Basic:
```yaml
steps:
- uses: actions/checkout@master
- uses: goit/setup-resharper@v1
  with:
    version: '2020.1'
- run: InspectCode <solution file>
```

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)
