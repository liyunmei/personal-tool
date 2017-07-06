## 本文记录的是git日志提交管理的格式工具
## validate-commit-msg && commitizen

具体使用规则可参考 `http://www.ruanyifeng.com/blog/2016/01/commit_message_change_log.html`
### **值得注意的是**

1.仔细阅读validate-commit-msg的[官方文档](https://github.com/conventional-changelog/validate-commit-msg)里面有段话

    This provides you a binary that you can use as a githook to validate the commit message.
    I recommend husky. You'll want to make this part of the commit-msg githook,
    e.g. when using husky, add "commitmsg": "validate-commit-msg" to your npm scripts in package.json.
    
  根据这个描述操作，validate-commit-msg才会真正被用到。

2.commitizen是撰写合格commit message的工具，命令是git cz；
  validate-commit-msg是检查Node项目的commit message是否符合格式的工具。
