Start or Focus 2.0.0
====================

Starts an application, or if it is already running, gives it focus.


[MIT License]
-------------


[Changelog]
-----------


Usage
-----

```
start-or-focus -- <name> [ <process> [ <command> ] ]
```
or:
```
start-or-focus ( --help | --version | -H | -h | -? | -V | -v )
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

### Examples

- ```
  start-or-focus -- "ghostwriter"
  ```
- ```
  start-or-focus -- "Geany" "geany"
  ```
- ```
  start-or-focus -- \
    "Mozilla Firefox" \
    "/usr/lib/firefox/firefox"
  ```
- ```
  start-or-focus -- \
    "Firefox Developer Edition" \
    "/opt/firefox-developer-edition/firefox"
  ```
- ```
  start-or-focus -- \
    "Chromium" \
    "chromium-browse" \
    "chromium-browser --incognito"
  ```
  (Starts Chromium in incognito mode.)


[MIT License]: ./LICENSE.md
[Changelog]: ./CHANGELOG.md
