# 小明词库插件：xiaoming-lexicon
本插件运行在 [小明机器人框架](https://github.com/TaixueChina/xiaoming-bot) 上。

词库是的主要功能是根据用户的定义，当用户发送**指定的触发词**后**随机**选择**定义好**的回答。

例如，用户可以定义触发词「投色子」对应六种随机回答：「一、二、三、四、五、六」，
当用户在群内发送「投色子」时，本插件会随机选择一个回答，例如「六」回应给发送者。

## 使用方法
1. 下载本插件最新的 RELEASE，放在小明本体/plugin下
1. 执行下列指令，或重启小明：
```xiaoming
刷新插件列表
启动插件 lexicons
```

## 词库分类
小明词库分三类：「群词库」「公共词库」和「私人词库」。

### 群词库
群词库是只能在指定群中触发的词库。

### 私人词库
私人词库是在小明所在的所有群中，只有自己才能触发的词库。

私人词库在QQ群中具有调用限制。

### 公共词库
公共词库是在小明所在的所有群中的所有成员都能触发的词库。建议最好是一些查询性信息，例如「服务器IP」「赞助方式」。

公共词库没有调用限制。