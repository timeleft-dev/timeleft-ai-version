# timeleft-ai version

`latest.json` holds the latest version of each timeleft-ai plugin, the versions before them, and when they were pushed. The plugins' version checks read it with one `curl`, and apply a two-hour grace before a pushed version counts. It is written by the `publish version` workflow of the plugins' own repository, through a deploy key that can write here and nowhere else. Nothing else belongs in this repository.
