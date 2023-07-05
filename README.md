# helix gruvbox community

This theme is just an extension of the [default helix gruvbox theme](https://github.com/helix-editor/helix/blob/master/runtime/themes/gruvbox.toml)
that changes some small things to make it look more like the [gruvbox community vim theme](https://github.com/gruvbox-community/gruvbox)

# setup

To use the plugin you can create a file in `.config/themes/{filename}.toml` and paste the content in it. \
My setup it's using stow so I clone the repo

```bash
git clone https://github.com/jeronimobarea/helix_gruvbox_community.git ~/.config/helix/themes/custom/helix_gruvbox_community
```

inside `.config/themes/custom/` and the just run `stow helix_gruvbox_community`
which will create a `symlink` in the `.config/themes` folder.
