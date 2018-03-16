# DlgSystem (Dialogue System) Plugin Example Project

Branch Unreal version: `4.18`

Example project for the [DlgSystem](https://gitlab.com/NotYetGames/DlgSystem/tree/4.18) plugin.

See the [Wiki](https://gitlab.com/NotYetGames/DlgSystem/wikis/home) for the manual and tutorials.
A blueprint only version of this example project can be downloaded from [here](https://www.dropbox.com/s/b946mre9zw5mlx7/DlgExampleBP.zip?dl=0).

## Clone
```sh
git clone -b 4.18 https://gitlab.com/NotYetGames/DlgSystemExample.git
```

## Update (pull) 

Update:
```sh
# Update this repo
git pull
# Update Subtree
git subtree pull --prefix Plugins/DlgSystem https://gitlab.com/NotYetGames/DlgSystem.git 4.18 --squash
```

## Push subtree modifications
NOTE: This is only if you modified the `Plugins/DlgSystem` subtree.
```sh
git subtree push --prefix=Plugins/DlgSystem https://gitlab.com/NotYetGames/DlgSystem.git 4.18
```

## Other
NOTE: repo was added with the following command.

NOTE: Branch `master` does no longer exist.
```sh
git subtree add --prefix Plugins/DlgSystem https://gitlab.com/NotYetGames/DlgSystem.git master --squash
```
