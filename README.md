# dotfiles
This is a repository to hold terminal settings to use in Codespaces

## Where do the files _go_?

### On Codespaces

When a codespace is built, this `dotfiles` directory is cloned to:
`/workspaces/.codespaces/.persistedshare/`

AS of this writing (September 2023), I'm pretty confused about where all the files live on codespaces.

| Variable | Location | Notes |
| ------- | ------- | ------- |
| `$HOME` | `/home/codespace` | `cd ~` goes to `/home/codespace` |
| `$ZSH` | `/home/codespace/.oh-my-zsh` |
| `$ZSH_CUSTOM` | `/home/codespace/.oh-my-zsh/custom` |

