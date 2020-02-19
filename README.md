# oclif-multi-ts-starter

OCLIF-generated multi-command starter on TypeScript

UNDER DEVELOPMENT

## Feature tags

- cli
- multi-command
- oclif
- starter
- template

---

## Authors

[Alexander Lapygin](https://github.com/AlexanderLapygin)

---

## Direct ancestors

TBD

---


## Install
```
npm i
```

---

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/oclif-multi-ts-starter.svg)](https://npmjs.org/package/oclif-multi-ts-starter)
[![Downloads/week](https://img.shields.io/npm/dw/oclif-multi-ts-starter.svg)](https://npmjs.org/package/oclif-multi-ts-starter)
[![License](https://img.shields.io/npm/l/oclif-multi-ts-starter.svg)](https://github.com/AlexanderLapygin/oclif-multi-ts-starter/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g oclif-multi-ts-starter
$ mycmd COMMAND
running command...
$ mycmd (-v|--version|version)
oclif-multi-ts-starter/0.1.0 win32-x64 node-v12.14.0
$ mycmd --help [COMMAND]
USAGE
  $ mycmd COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`mycmd hello [FILE]`](#mycmd-hello-file)
* [`mycmd help [COMMAND]`](#mycmd-help-command)

## `mycmd hello [FILE]`

describe the command here

```
USAGE
  $ mycmd hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ mycmd hello
  hello world from ./src/hello.ts!
```

_See code: [src\commands\hello.ts](https://github.com/AlexanderLapygin/oclif-multi-ts-starter/blob/v0.1.0/src\commands\hello.ts)_

## `mycmd help [COMMAND]`

display help for mycmd

```
USAGE
  $ mycmd help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.2.3/src\commands\help.ts)_
<!-- commandsstop --> 

---

### License

Licensed under the [MIT license](./LICENSE).
