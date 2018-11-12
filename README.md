## Installation

To install rbenv-each, clone this repository into your rbenv plugins directory. (You'll need a recent version of rbenv that supports plugin bundles.)


```
$ mkdir -p "$(rbenv root)"/plugins
$ git clone https://github.com/rbenv/rbenv-each.git "$(rbenv root)"/plugins/rbenv-each
```

## Usage

```
$ rbenv help each
```

Verbose mode will print a header for each ruby so you can distinguish
the output.

**Note**: [Version aliases][rbenv-aliases] (versions that are just symlinks pointing to another rbenv version) are skipped when iterating through the list of rbenv versions.

### Examples:

```
$ rbenv each bundle install
$ rbenv each -v rake test
```

[rbenv-aliases]: https://github.com/rbenv/rbenv-aliases
