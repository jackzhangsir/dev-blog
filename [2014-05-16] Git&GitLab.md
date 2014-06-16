
#Git&GitLab

- [ ] [git checkout之一 HEAD基本和detached 状态](http://blog.csdn.net/csfreebird/article/details/7583363)
- [ ] [git-flow 备忘清单](http://danielkummer.github.io/git-flow-cheatsheet/index.zh_CN.html)
- [ ] [真正理解 git fetch, git pull 以及 FETCH_HEAD](https://ruby-china.org/topics/4768)



## 常见使用


1.撤消提交(两种情形) 


第一种：撤消提交后需要保存对文件的修改或者新增的文件

`

git reset HEAD~1

`

第二种：撤消提交后不需要保存对文件的修改或者新增的文件

`

git reset --hard HEAD~1

`

[help](http://hi.baidu.com/configuration/item/5a3f2b9a94f8d935336eeba9)

2.撤消缓存区

stage -> unstage

`
git reset HEAD filename
`
> 终端使用时会给你很好的提示。


