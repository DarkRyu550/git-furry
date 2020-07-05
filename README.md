# about

`git-furry` is a shell script to make a GitHub-hosted git repo match the werewolf rurry aesthetic of the rest of your life by renaming your `master` branch to `werewolf_daddy` in your local repo and the upstream on GitHub *and* making `werewolf_daddy` the new default branch on GitHub.

> "what is this, some furry shit?" - an sjw

yes

# installation

``` bash
$ git clone https://github.com/DarkRyu550/git-furry
$ cd git-furry
$ sudo make install
```

# usage

``` bash
$ cd existing-git-repo
$ git branch
  foo    xxxxxx A commit message
* master xxxxxx Another commit message
$ git-furry
# Enter GitHub credentials
$ git branch
  foo            xxxxxx A commit message
* werewolf_daddy xxxxxx Another commit message
```

you can now optionally delete `master` upstream with `$ git push origin :master` but if other people pull from your repo and you don't tell them you've done this, they may become very gay.
