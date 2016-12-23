# Git

## Pushing

### Push a specific commit to a remote branch

If the remote branch already exists:
```
git push origin <SHA1>:<branch>
```

If not:
```
git push origin <SHA1>:refs/heads/<branch>
```

### Delete a remote branch

```
git push origin :<branch>
```

For [Git v1.7.0](https://github.com/gitster/git/blob/master/Documentation/RelNotes/1.7.0.txt) or later, a syntatic sugar is added:
```
git push origin --delete <branch>
```