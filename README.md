# vimfiles

This is my collection of localised vimfiles, they are based upon [vim bootstrap](https://vim-bootstrap.com/)

To generate the base file use:
```
curl 'http://vim-bootstrap.com/generate.vim' --data 'langs=go&langs=rust&editor=vim' > ~/.vimrc
```

and then symlink `.vimrc.local` and `.vimrc.local.bundles` to your home directory.

```
cd
ln -s workspace/vimfiles/vimrc.local .vimrc.local
ln -s workspace/vimfiles/vimrc.local.bundles .vimrc.local.bundles
```


## Update

Regenerate the `.vimrc` file from above and git update this directory
