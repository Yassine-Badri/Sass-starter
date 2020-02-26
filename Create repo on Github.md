### mkdir repo && cd repo

```sh
$ git remote add origin /path/to/origin.git
$ git add .
```

### Oops! Never committed!

```sh
$ git push -u origin master
$ error: src refspec master does not match any.
```

## All I had to do was:

```sh
$ git commit -m "initial commit"
$ git push origin master
```
