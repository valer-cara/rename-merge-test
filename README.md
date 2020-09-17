# rename-merge-test
Git experiment to test merge to a file that's been renamed

## How to check the outcome of a merge


Here's how [the branches look](https://github.com/valer-cara/rename-merge-test/network)

```
# Branch with changes to /foo file
git checkout foo

# Branch with conflicting changes to /foo file & a rename of /foo to /foo2
git rebase -i renames
```
