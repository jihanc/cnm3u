# 使用说明:

每天自动获取上游仓库[iptv-org/iptv](https://github.com/iptv-org/iptv)的中国源，并生成自己的 m3u 列表:

```
# m3u链接
https://jihanc.github.io/cnm3u/cn1080.m3u

```

# 项目原地址 : [kaigedong/cnm3u](https://github.com/kaigedong/cnm3u)

```

## 生成规则：

- 首先删除掉黑名单[blacklist.txt](./blacklist.txt)

- 然后导出白名单里的列表[whitelist.txt](./whitelist.txt)

- 然后使用 IPTV Checker 对源的有效性进行筛选

- 自动提交到[gh](https://github.com/jihanc/cnm3u/tree/gh)分支，并使用 GithubPage 进行托管
