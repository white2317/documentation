---
title: npm-bugs
section: 1
description: Report bugs for a package in a web browser
github_repo: npm/cli
github_branch: v7
github_path: docs/content/commands/npm-bugs.md
redirect_from:
  - /cli-documentation/v7/bugs
  - /cli-documentation/v7/cli-commands/bugs
  - /cli-documentation/v7/cli-commands/npm-bugs
  - /cli-documentation/v7/commands/bugs
  - /cli-documentation/v7/commands/npm-bugs
  - /cli-documentation/v7/npm-bugs
  - /cli/v7/bugs
  - /cli/v7/cli-commands/bugs
  - /cli/v7/cli-commands/npm-bugs
  - /cli/v7/commands/bugs
  - /cli/v7/npm-bugs
---

### Synopsis

```bash
npm bugs [<pkgname> [<pkgname> ...]]

aliases: issues
```

### Description

This command tries to guess at the likely location of a package's bug
tracker URL or the `mailto` URL of the support email, and then tries to
open it using the `--browser` config param. If no package name is provided, it
will search for a `package.json` in the current folder and use the `name` property.

### Configuration

<!-- AUTOGENERATED CONFIG DESCRIPTIONS START -->
<!-- automatically generated, do not edit manually -->
<!-- see lib/utils/config/definitions.js -->
#### `browser`

* Default: OS X: `"open"`, Windows: `"start"`, Others: `"xdg-open"`
* Type: null, Boolean, or String

The browser that is called by npm commands to open websites.

Set to `false` to suppress browser behavior and instead print urls to
terminal.

Set to `true` to use default system URL opener.

<!-- automatically generated, do not edit manually -->
<!-- see lib/utils/config/definitions.js -->

#### `registry`

* Default: "https://registry.npmjs.org/"
* Type: URL

The base URL of the npm registry.

<!-- automatically generated, do not edit manually -->
<!-- see lib/utils/config/definitions.js -->

<!-- AUTOGENERATED CONFIG DESCRIPTIONS END -->

### See Also

* [npm docs](/cli/v7/commands/npm-docs)
* [npm view](/cli/v7/commands/npm-view)
* [npm publish](/cli/v7/commands/npm-publish)
* [npm registry](/cli/v7/using-npm/registry)
* [npm config](/cli/v7/commands/npm-config)
* [npmrc](/cli/v7/configuring-npm/npmrc)
* [package.json](/cli/v7/configuring-npm/package-json)
