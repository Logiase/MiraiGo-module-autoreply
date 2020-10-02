# MiraiGo-module-autoreply

ID: logiase.autoreply

Module for [MiraiGo-Template](https://github.com/Logiase/MiraiGo-Template)

## 使用方法

在适当位置引入本包

```go

package example

imports (
    // ...
    
    _ "github.com/Logiase/MiraiGo-module-autoreply"

    // ...
)

// ...


```

配置文件默认位置 ./autoreply.yaml

同时可以在全局配置 application.yaml 中 设置 logiase.autoreply.path 键值

配置文件请遵循 yaml 规则

参照 [autoreply](./autoreply.yaml) 编写相应回复

目前仅支持文本消息，其他消息类型会抽时间~~咕咕咕~~

