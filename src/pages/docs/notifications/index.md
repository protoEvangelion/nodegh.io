---
title: "Notifications"
description: "Display The Latest Repo Activities & Watch For Repo Activity"
layout: "guide"
icon: "cloud"
weight: 3
---

###### {$page.description}

<article id="1">

```shell
gh notification
```

#### Alias:

```shell
gh nt
```

## Latest

Option           | Usage        | Type
---              | ---          | ---
`-l`, `--latest` | **Required** | `Boolean`
`--remote`       | *Optional*   | `String`
`-r`, `--repo`   | *Optional*   | `String`
`-u`, `--user`   | *Optional*   | `String`

#### Examples

* **Shortcut** for displaying the latest activities on the current repository.

```shell
gh nt
```

* Display the latest activities on a certain repository.

```shell
gh nt --latest --user eduardolundgren --repo node-gh
```

</article>


<article id="2">

## Watch

Option           | Usage        | Type
---              | ---          | ---
`-w`, `--watch`  | **Required** | `Boolean`
`--remote`       | *Optional*   | `String`
`-r`, `--repo`   | *Optional*   | `String`
`-u`, `--user`   | *Optional*   | `String`

#### Examples

* Watch for any activity on the current repository.

```shell
gh nt --watch
```

* Watch for any activity on a certain repository.

```shell
gh nt --watch --user eduardolundgren --repo node-gh
```

</article>