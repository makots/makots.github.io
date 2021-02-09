---
layout: single
title:  "GitHub CLI のインストール"
date:   2021-02-08 18:00:00 +0900
categories: git
---

MacOSに GitHub CLI をインストールした。

参照: [GitHub CLI](https://cli.github.com/manual/)

```shell
$ brew install gh
$ gh auth login
? What account do you want to log into? GitHub.com
? How would you like to authenticate? Login with a web browser

! First copy your one-time code: ********
- Press Enter to open github.com in your browser...
✓ Authentication complete. Press Enter to continue...

? Choose default git protocol SSH
- gh config set -h github.com git_protocol ssh
✓ Configured git protocol
✓ Logged in as **********
$ gh config set editor iTerm
$
```