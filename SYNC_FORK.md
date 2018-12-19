# How to sync this fork with the upstream repo

## Make sure you have the `upstream` remote

```sh
git remote -v
git remote add upstream https://github.com/terraform-providers/terraform-provider-azurerm.git
```

## Sync

```sh
git fetch upstream
git checkout master
git merge upstream/master
git push
```
