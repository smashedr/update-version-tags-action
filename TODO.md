# TODO

- Delete [dist](dist)
- Delete [commit-checklist.json](commit-checklist.json)
- Confirm [jsconfig.json](jsconfig.json) is useful
- Create release branch

```shell
#git clone ...

git checkout --orphan release
git rm -rf .

#add new code -- RELEASE.md

git add .
git commit -m "Creating Release Branch"
git push -u origin release
```

- Delete [RELEASE.md](RELEASE.md)
- Create stable fork and update [release.yaml](.github/workflows/release.yaml)
- Cleanup [TODO.md](TODO.md)

> Merge PR

- Update [release.yaml](.github/workflows/release.yaml)
- Delete [TODO.md](TODO.md)
