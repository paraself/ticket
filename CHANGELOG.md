# 更新日志

## v1.2.0
* `master` 分支移除所有关于 LeanCloud 定制的元素，方便开发者 fork 后使用或进行二次开发。所有 LeanCloud 定制内容提交在 `leancloud` 分支，开发者可以作为二次开发的参考。

## v1.1.0

* 增加用户 Profile 页面，查看和修改个人信息。

**注意**：数据库格式有变化，请执行下面命令做数据订正：

```
$(lean up)
npm run migrate
```

