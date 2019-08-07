
# 分支改造
```bash
# 强制用分支覆盖本地
git fetch --all && git reset --hard origin/0405 && git pull

# 上级项目添加当前git为子模块
git submodule add git@github.com:houcl/hexo-theme-icarus.git themes/icarus

```