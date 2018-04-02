Changelog
=========

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog] and this project adheres to [Semantic
Versioning].


[Unreleased]
------------

### Fixed

- Line feed escapes from `\n` to `\\n`.


[1.1.0] – 2018-03-14
--------------------

### Added

- Changelog based on [Keep a Changelog].
- `set -e`, so that the script fails fast on errors.

### Fixed

- Not quoting `$application_process`.


[1.0.1] – 2018-03-14
--------------------

### Fixed

- No format string passed to `printf`.


[1.0.0] – 2018-02-05
--------------------

### Added

- Starting and focusing applications.


[Keep a Changelog]: http://keepachangelog.com/en/1.0.0/
[Semantic Versioning]: http://semver.org/spec/v2.0.0.html
[Unreleased]:
  https://github.com/henrik-leppa/start-or-focus/compare/1.1.0...HEAD
[1.1.0]: https://github.com/henrik-leppa/start-or-focus/compare/1.0.1...1.1.0
[1.0.1]: https://github.com/henrik-leppa/start-or-focus/compare/1.0.0...1.0.1
[1.0.0]:
  https://github.com/henrik-leppa/start-or-focus/compare/26ba0fa2dc85059609fa88e4b52decf21796bf8d...1.0.0
