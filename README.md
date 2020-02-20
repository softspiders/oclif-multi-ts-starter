# oclif-multi-ts-starter

OCLIF-generated multi-command starter on TypeScript

## Feature tags

- cli
- multi-command
- oclif
- starter
- template
- typescript

---

## Authors

[Alexander Lapygin](https://github.com/AlexanderLapygin) <<alexanderlapygin@gmail.com>>

---

## Direct ancestors

[node-cli-starter](https://github.com/softspiders/node-cli-starter)

---


## Install
```
npm i
```

---

## Usage

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

## Commands
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

---

### License

Licensed under the [MIT license](./LICENSE).
