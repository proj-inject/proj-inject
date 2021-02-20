# proj-inject

Utility to inject standardized or templated content into projects.

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/proj-inject.svg)](https://npmjs.org/package/proj-inject)
[![Codecov](https://codecov.io/gh/brennanfee/proj-inject/branch/master/graph/badge.svg)](https://codecov.io/gh/brennanfee/proj-inject)
[![Downloads/week](https://img.shields.io/npm/dw/proj-inject.svg)](https://npmjs.org/package/proj-inject)
[![License](https://img.shields.io/npm/l/proj-inject.svg)](https://github.com/brennanfee/proj-inject/blob/master/package.json)

<!-- toc -->

- [Usage](#usage)
- [Commands](#commands)
<!-- tocstop -->

# Usage

<!-- usage -->

```sh-session
$ npm install -g proj-inject
$ proj-inject COMMAND
running command...
$ proj-inject (-v|--version|version)
proj-inject/0.1.0 linux-x64 node-v15.9.0
$ proj-inject --help [COMMAND]
USAGE
  $ proj-inject COMMAND
...
```

<!-- usagestop -->

# Commands

<!-- commands -->

- [`proj-inject hello [FILE]`](#proj-inject-hello-file)
- [`proj-inject help [COMMAND]`](#proj-inject-help-command)

## `proj-inject hello [FILE]`

describe the command here

```
USAGE
  $ proj-inject hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ proj-inject hello
  hello world from ./src/hello.ts!
```

_See code:
[src/commands/hello.ts](https://github.com/brennanfee/proj-inject/blob/v0.1.0/src/commands/hello.ts)_

## `proj-inject help [COMMAND]`

display help for proj-inject

```
USAGE
  $ proj-inject help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code:
[@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.2/src/commands/help.ts)_

<!-- commandsstop -->

## License

[MIT](license.md) © 2021 [Brennan Fee](https://github.com/brennanfee)
