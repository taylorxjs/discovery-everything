

# 简历

https://jianlixiazai.cn/ 简历下载网，有你想要的**各种款式简历模板，全部都一键免费下载**，还可以自由编辑，想怎么改就怎么改，设计简约大方。

# interview

AI面试神器助手：interviewpass.top



# 离职

**辞职信网**：www.cizhixin.com

这个网站里面有着大量各行各业、不同群体、不同理由的辞职信模板可供免费使用。



# 其他

[code996](https://hellodigua.github.io/code996/#/)

源码链接：https://github.com/hellodigua/code996

一个分析工具，它可以统计 Git 项目的 commit 时间分布，进而推导出这个项目的编码工作强度。

本地分析：在 Git 项目的根目录，执行以下命令：

~~~powershell
curl -fsSL https://fastly.jsdelivr.net/gh/hellodigua/code996/bin/code996.sh | bash
~~~

在线分析 Gitlab 项目，可以使用该 [油猴脚本](https://greasyfork.org/en/scripts/452007-gitlab-996-index-statistic)

无法使用 curl 的 Windows 用户， 可下载 [该脚本](https://fastly.jsdelivr.net/gh/hellodigua/code996/bin/code996.sh) 并使用

备用脚本地址：

```powershell
curl -fsSL https://raw.githubusercontent.com/hellodigua/code996/master/bin/code996.sh | bash
```

工作原理：

1. 使用 git-log 对项目当前的分支进行查询，得到以小时汇总和以天汇总的 commit 统计结果

2. 将本地脚本得到的查询结果转为 URL 参数，并打开 URL 到浏览器

3. 从 URL 拿到数据，并使用一些规则处理，并将结果可视化展现

