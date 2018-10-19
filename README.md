# vimfiles

This is my collection of localised vimfiles, they are based upon vim bootstrap

To generate the base file use:
```
curl 'http://vim-bootstrap.com/generate.vim' --data 'langs=go&langs=rust&editor=vim' > ~/.vimrc
```

and then symlink `.vimrc.local` and `.vimrc.local.bundles` to your home directory.

## Update

Regenerate the `.vimrc` file from above and git update this directory
