### Natural Language procesing

Here, Large data file has been uploaded with Git-lfs (https://git-lfs.com/)

Install the  plugin as mentioned in above  page.
```
git lfs install
```

Commands to add file in git-lfs:
```
git lfs track "data.csv" // tracking file in lfs and .gitattributes file will be created.

git add .gitattributes // adding attributes file in git.

git lfs migrate import (command to import file in large file system)

git add data.csv
git commit -m "Add large file"
git push origin main

```

