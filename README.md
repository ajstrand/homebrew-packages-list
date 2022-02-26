### From stack overflow 

brew bundle may also be interesting if you are asking because you want to manage your brew installation. This includes casks, which brew list does not. It is aimed at having reproducible Homebrew setups.

# creates Brewfile in the current directory from currently-installed packages
`brew bundle dump`
# edit Brewfile
# install everything from the Brewfile
`brew bundle`
You can use the --global flag to operate on your ~/.Brewfile and -f/--force to force overwriting of your existing file (for installation, this will force uninstallation of not-listed packages).