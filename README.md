# npmfzf

npm scripts fuzzy finder and runner

## Prerequisites

* [fzf](https://github.com/junegunn/fzf)
* [jq](https://stedolan.github.io/jq/)
* [rg](https://github.com/BurntSushi/ripgrep)

## Install

```sh
sudo sh -c "curl https://raw.githubusercontent.com/kubejm/npmfzf/master/npmfzf \
       -o /usr/local/bin/npmfzf && \
       chmod +x /usr/local/bin/npmfzf"
```

## Usage

Run `npmfzf` within a directory where `package.json` is present.
