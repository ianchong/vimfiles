# vimfiles
Use git submodules to manage plugins

## install plugins
git submodule add https://github.com/username/PluginRepoName.git pack/plugins/start/PluginRepoName

## remove plugins
git submodule deinit <plugin-filepath>
git rm -r <plugin-filepath>
rm -rf .git/modules/<plugin-filepath>

## update all plugins
git submodule update --remote --merge
