# git annex parity

Some experimental scripts for using parity with git-annex

git-annex-par2 is a git-annex module that generates par2 parity files for a respective file, inside the objects directory.

You can pass along matching options, so you can do things like generate local parity files for when you don't have more than one copy: `git annex par2 create --not --copies=2`

