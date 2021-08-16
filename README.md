# PKGBUILD_evolus_pencil
AUR package for evolus pencil (An open-source GUI prototyping tool)


# How to install 
1. `git clone`
2. `makepkg -C -f -i`

Or use your favorite AUR helper with the AUR package https://aur.archlinux.org/packages/pencil-git/


# How to maintain

Maintenance is done in [AUR git](https://aur.archlinux.org/packages/pencil-git/)
following [AUR submission guidelines](https://wiki.archlinux.org/title/AUR_submission_guidelines)

```
$ git clone ssh://aur@aur.archlinux.org/pencil-git

$ cd evolus-pencil-git-dev-branch/

#perform wanted changes

$ updpkgsums
$ makepkg --printsrcinfo > .SRCINFO

#git-add-and-commit wanted changes

# git push
```
