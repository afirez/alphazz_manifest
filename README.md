# alphazz repo manifast

```bash
# 下载 repo
$ mkdir ~/bin
$ PATH=~/bin:$PATH

$ curl https://storage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
$ chmod a+x ~/bin/repo

# 配置 git

# 初始化 alphazz
$ mkdir alphazz && cd alphazz

$ repo init -u https://github.com/afirez/alphazz_manifest.git

$ repo sync

¥ repo forall –c ‘cmd1; cmd2; ...’

```