Steps for repository recreation (require [git-filter-repo](https://github.com/newren/git-filter-repo/))

```
$ git clone readthedocs.org dev-docs --no-local
$ cd dev-docs
$ git-filter-repo --path docs/development/ --path docs/conf.py
```

To install git-filter-repo, it suffices with

```
$ pipx install git-filter-repo
```
