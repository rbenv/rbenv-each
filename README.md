## Installation

To install rbenv-each, clone this repository into your ~/.rbenv/plugins directory. (You'll need a recent version of rbenv that supports plugin bundles.)


```
$ mkdir -p ~/.rbenv/plugins
$ cd ~/.rbenv/plugins
$ git clone https://github.com/chriseppstein/rbenv-each.git
```

## Usage

You can get help for the `each` command by passing the `-h` option.

```
$ rbenv each -h
Usage: rbenv each [-v] ...
       -v Verbose mode. Prints a header for each ruby.
```

Verbose mode will print a header for each ruby so you can distinguish
the output.

### Examples:

```
$ rbenv each bundle install
$ rbenv each -v rake test
```
