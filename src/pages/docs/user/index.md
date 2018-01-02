---
title: "User"
description: "Login & Logout For Your Node GH User"
layout: "guide"
icon: "flash"
weight: 6
---

###### {$page.description}

<article id="1">
```shell
gh user
```

#### Alias:

```shell
gh us
```

## Login/Logout

Option            | Usage        | Type
---               | ---          | ---
`-l`, `--login`   | **Required** | `Boolean`
`-L`, `--logout`  | **Required** | `Boolean`

#### Examples

* Login or show current logged in GitHub user.

```shell
gh user --login
```

* Logout current GitHub account.

```shell
gh user --logout
```


</article>


<article id="2">

## Whoami

Option             | Usage        | Type
---                | ---          | ---
`-w`, `--whoami`   | **Required** | `Boolean`

#### Examples

* Prints your username to stdout.

```shell
gh user --whoami
```
</article>
