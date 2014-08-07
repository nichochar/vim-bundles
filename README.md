vim-bundles
===========

All of the VIM pathogen bundles I use

If you want to install one, I would use [pathogen](https://github.com/tpope/vim-pathogen)

  a. **Move to VIM bundles:** 

            $ cd ~/.vim/bundle
            
  b. **Clone whatever bundle you have found the remote repo of (example css colors):**
  
            $ git clone git://github.com/altercation/vim-colors-solarized.git

You can get pathogen [here](https://github.com/tpope/vim-pathogen), thanks Tim Pope!

ProTip: if you want to update all the bundles you just have to navigate to your bundles/ dir and run
```
git submodule foreach git pull origin master
```
