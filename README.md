# rsharifnasab.pdf

### Intro

Get to know me!

### Pre-Build version

You can check it on Github Releases in PDF format.

### Build from source

1. prepare the system (Do this only once)

```sh
yay -S texlive-core tllocalmgr-git # install on arch
yay -S textlive-fontsextra
tllocalmgr install moderncv academicons fontawesome5 multirow arydshln
sudo texhash
```

- Make resume

```sh
latexmk main.tx
```

- clean the folder
  this will remove all ignored files from the local repo. [how?](https://stackoverflow.com/a/46273201/10999348)

```sh
git clean -dfX
```
