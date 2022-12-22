# More details

[Shared Notion Page](https://www.notion.so/Configure-Nvim-738eb48729e14819aeeb302c4e347ce1)

## Location:

`~/.config/nvim`

## Initialize

Open `init.vim` and add the following line:
`vim init.vim` and run `:PlugInstall`

## Zshrc

`zshrc` is located into `~/.zshrc`

### Custom aliases

```
alias v=openNvim

function openNvim {
   if [ $# -eq 0 ]; then
     nvim ./
   else
     nvim $1
   fi
 }
```
