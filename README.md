# zinit-rbenv

`rbenv init` with [zinit](https://github.com/zdharma/zinit). It makes zsh startup faster.

## Usage

```bash
# when rbenv command is in your path (e.g. installed with Homebrew)
zinit ice wait"0" lucid
zinit light htlsne/zinit-rbenv
```

or

```bash
path=($HOME/.rbenv/bin(N-/) $path)
zinit ice wait"0" lucid has"rbenv"
zinit light htlsne/zinit-rbenv
```
