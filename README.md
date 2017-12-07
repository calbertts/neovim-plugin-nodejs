# neovim-plugin-nodejs
I made this because the poor documentation about how to make a simple plugin work.

Copy this project in your Neovim runtime path, usually: `/Users/<USER>/.config/nvim/rplugin/node`
If `rplugin/node` path doesn't exist, create it.

Then inside de project run:
```
$ npm i
$ npm run build // babel dependency
```
After build, you need to run in Neovim:
```
:UpdateRemotePlugins
```
And then restart Neovim, that's it :)

Now you should be able to run the example command `JSHostTestCmd`
