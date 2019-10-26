# zplugin-rbenv

`rbenv init` with [zplugin](https://github.com/zdharma/zplugin). It makes zsh startup faster.

## Usage

```bash
# when rbenv command in your path (e.g. installed with Homebrew)
zplugin ice wait"0" lucid
zplugin light htlsne/zplugin-rbenv
```

or

```bash
path=($HOME/.rbenv/bin(N-/) $path)
if type rbenv > /dev/null 2>&1; then
    zplugin ice wait"0" lucid
    zplugin light htlsne/zplugin-rbenv
fi
```
