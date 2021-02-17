# Tinsel Application Template

Clone this repo if you want to make a Tinsel application, either
baremetal or using POLite.  It uses Tinsel as a submodule, so be sure
to do a recursive clone.

```bash
$ git clone --recursive https://github.com/POETSII/tinsel-app-template
```

As changes are made to Tinsel, you should try to keep your submodule
up to date:

```bash
$ cd tinsel
$ git pull origin master
```

If you want put your application `MyApp` on github then, on github,
create a new repo called `MyApp`.  Then, in your `tinsel-app-template`
repo, do:

```bash
$ git remote set-url origin https://github.com/POETSII/MyApp.git
$ git push origin master
```

Or, if you prefer SSH rather than HTTPS, change the first command to:

```bash
$ git remote set-url origin git@github.com:POETSII/MyApp.git
```

Take care *not* to push to `tinsel-app-template` itself!
