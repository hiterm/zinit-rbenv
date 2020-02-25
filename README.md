# zinit-rbenv

`rbenv init` with [zinit](https://github.com/zdharma/zinit). It makes zsh startup faster.

## Usage

```bash
# when rbenv command in your path (e.g. installed with Homebrew)
zinit ice wait"0" lucid
zinit light htlsne/zinit-rbenv
```

or

```bash
path=($HOME/.rbenv/bin(N-/) $path)
if type rbenv > /dev/null 2>&1; then
    zinit ice wait"0" lucid
    zinit light htlsne/zinit-rbenv
fi
```
