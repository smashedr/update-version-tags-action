# TODO

- Delete [dist](dist)
- Delete [commit-checklist.json](commit-checklist.json)
- Confirm [jsconfig.json](jsconfig.json) is useful
- Create release [branch](#create-release-branch)
- Delete [RELEASE.md](RELEASE.md)
- Delete [TODO.md](TODO.md)

## Create Release Branch

```shell
#git clone ...

git checkout --orphan release
git rm -rf .

#add new code -- RELEASE.md

git add .
git commit -m "Creating Release Branch"
git push -u origin release
```
