# Landing for Contest #1

That's my practise in Git merging. There I merged 2 branches which was conflicting with each other using Meld, Gitg and git-commands:

    git checkout master 
    git merge other_branch 
    # the merge reports conflicts which we need to resolve 
    git add -u 
    git commit -m "a merge commit message"

It's a landing page for the contest of the Python programmers. Work is still in progress. Only a static HTML page is available now.

# How to launch

```bash
$ python3 -m http.server
```

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
