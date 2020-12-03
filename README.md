<!--
https://readme42.com
-->



[![](https://img.shields.io/badge/OS-Unix-blue.svg?longCache=True)]()
[![](https://img.shields.io/pypi/v/dir-exec.svg?maxAge=3600)](https://pypi.org/project/dir-exec/)
[![](https://img.shields.io/npm/v/dir-exec.svg?maxAge=3600)](https://www.npmjs.com/package/dir-exec)[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![](https://github.com/andrewp-as-is/dir-exec/workflows/tests42/badge.svg)](https://github.com/andrewp-as-is/dir-exec/actions)

### Installation
```bash
$ [sudo] pip install dir-exec
```

```bash
$ [sudo] npm i -g dir-exec
```

#### Examples
```bash
$ find ~/git/gists -type d -mindepth 1 -maxdepth 1 -print0 | xargs -0 dir-exec command
```

execute function
```bash
func() {
    ...
}
export -f func
find ~/git/gists -type d -mindepth 1 -maxdepth 1 -print0 | xargs -0 dir-exec func
```

<p align="center">
    <a href="https://readme42.com/">readme42.com</a>
</p>
