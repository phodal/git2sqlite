# Git to SQLite

A research on how to save Git log to database for [Coco](https://github.com/inherd/coco)

Architecture

1. parse git log
2. parse log by line to commit
3. save commit to json file
4. read json file and save to db

## Performance logs

### Without Changes

| Project Name     | Project Commits | Time   |
|------------------|-----------------|--------|
| Nginx            | 6805            | 32s    |
| Redis            | 10009           | 67s    |
| Spring Framework | 22133           | 706s   |


License
---

@ 2020~2021 This code is distributed under the MIT license. See `LICENSE` in this directory.
