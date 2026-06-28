#### To list only the ignored files recursively across your entire project repository, use git ls-files
```
git ls-files --others --ignored --exclude-standard
```

#### Only Tracked, Modified Files: Add --modified
```
git ls-files --modified | xargs realpath
```

#### Only New, Staged Files: Add --staged
```
git ls-files --staged | xargs realpath
```

#### Only New, Untracked Files: Add --others --exclude-standard
```
git ls-files --others --exclude-standard | xargs realpath
```

####
```
```

####
```
```

####
```
```

####
```
```
