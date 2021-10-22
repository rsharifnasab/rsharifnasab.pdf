## How to

- prepare system
  Do this only once

```bash
yay -s texlive-core tllocalmgr
tllocalmgr install moderncv academicons fontawesome5 multirow arydshln
sudo texhash

```

- Make resume

```bash
latexmk  main.tx
```

- clean the folder
  this will remove all ignored files from the local repo. [explain](https://stackoverflow.com/a/46273201/10999348)

```sh
git clean -dfX
```
