start-or-focus
==============

Starts an application, or if it is already running, gives it focus.


Usage
-----

```
start-or-focus <name> [ <process> [ <command> ] ]
```
or:
```
start-or-focus [ --help | --version | -H | -h | -? | -V | -v ]
```

### Options

- `--help, -H, -h, -?`
  - Print the usage message.
- `--version, -V, -v`
  - Print version and copyright information.
- `<name>`
  - Name of the application as it appears in the window (case insensitive).
- `<process>`
  - Name of the application's process (case sensitive). If not given, assumed to
    be same as `<name>`.
- `<command>`
  - The command used to start the application. If not given, assumed to be same
    as `<process>`.
