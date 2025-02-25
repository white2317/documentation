---
title: npm-bin
section: 1
description: Display npm bin folder
github_repo: npm/cli
github_branch: v7
github_path: docs/content/commands/npm-bin.md
redirect_from:
  - /cli-documentation/v7/bin
  - /cli-documentation/v7/cli-commands/bin
  - /cli-documentation/v7/cli-commands/npm-bin
  - /cli-documentation/v7/commands/bin
  - /cli-documentation/v7/commands/npm-bin
  - /cli-documentation/v7/npm-bin
  - /cli/v7/bin
  - /cli/v7/cli-commands/bin
  - /cli/v7/cli-commands/npm-bin
  - /cli/v7/commands/bin
  - /cli/v7/npm-bin
---

### Synopsis

```bash
npm bin [-g|--global]
```

Note: This command is unaware of workspaces.

### Description

Print the folder where npm will install executables.

### Configuration

<!-- AUTOGENERATED CONFIG DESCRIPTIONS START -->
<!-- automatically generated, do not edit manually -->
<!-- see lib/utils/config/definitions.js -->
#### `global`

* Default: false
* Type: Boolean

Operates in "global" mode, so that packages are installed into the `prefix`
folder instead of the current working directory. See
[folders](/cli/v7/configuring-npm/folders) for more on the differences in behavior.

* packages are installed into the `{prefix}/lib/node_modules` folder, instead
  of the current working directory.
* bin files are linked to `{prefix}/bin`
* man pages are linked to `{prefix}/share/man`

<!-- automatically generated, do not edit manually -->
<!-- see lib/utils/config/definitions.js -->

<!-- AUTOGENERATED CONFIG DESCRIPTIONS END -->

### See Also

* [npm prefix](/cli/v7/commands/npm-prefix)
* [npm root](/cli/v7/commands/npm-root)
* [npm folders](/cli/v7/configuring-npm/folders)
* [npm config](/cli/v7/commands/npm-config)
* [npmrc](/cli/v7/configuring-npm/npmrc)
