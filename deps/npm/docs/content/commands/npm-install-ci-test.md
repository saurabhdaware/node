---
title: npm-install-ci-test
section: 1
description: Install a project with a clean slate and run tests
---

### Synopsis

```bash
npm install-ci-test

alias: npm cit
```

### Description

This command runs `npm ci` followed immediately by `npm test`.

### Configuration

<!-- AUTOGENERATED CONFIG DESCRIPTIONS START -->
<!-- automatically generated, do not edit manually -->
#### `ignore-scripts`

* Default: false
* Type: Boolean

If true, npm does not run scripts specified in package.json files.

Note that commands explicitly intended to run a particular script, such as
`npm start`, `npm stop`, `npm restart`, `npm test`, and `npm run-script`
will still run their intended script if `ignore-scripts` is set, but they
will *not* run any pre- or post-scripts.

#### `script-shell`

* Default: '/bin/sh' on POSIX systems, 'cmd.exe' on Windows
* Type: null or String

The shell to use for scripts run with the `npm exec`, `npm run` and `npm
init <pkg>` commands.

<!-- AUTOGENERATED CONFIG DESCRIPTIONS END -->

### See Also

* [npm install-test](/commands/npm-install-test)
* [npm ci](/commands/npm-ci)
* [npm test](/commands/npm-test)