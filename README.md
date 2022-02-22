Gitstats
=

#### [Origin README](doc/README)

#### Quick Start
```cmd
python3 gitstats <git_repo_dir> <html_output_dir>
```
conf can be set in `gitstats.conf` variable<br>
download [gnuplot](http://www.gnuplot.info/download.html)

#### Features
- support Windows
- support Python3

#### Issue
- `gnuplot --version` command get no result by `Popen` but it can generate images well,
   so removed `gnuplot` version check
- to show Chinese character in images, at `lines_of_code_by_author.plot` and `commits_by_author.plot` 
  add `font "Microsoft Yahei UI, 10"` option


