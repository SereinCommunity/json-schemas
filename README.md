# PluginInfoJsonSchema

插件信息的JSON文件Schema规范

## 使用方法

新建一个JSON文件，复制如下文本到该文件中

```jsonc
{
    "$schema": "https://sereincommunity.github.io/PluginInfoJsonSchema/v1.json",
}
```

## 示例

```jsonc
{
    "$schema": "https://sereincommunity.github.io/PluginInfoJsonSchema/v1.json",

    "name": "hello world",                // 插件名称
    "id": "hello-world",                  // 插件ID
    "author": "Zaitonn",                  // 插件作者
    "version": "1.2.3.4",                 // 插件版本
    "targetingSereinVersion": "2.0.0",    // 适用的Serein的最低版本
    "targetingServerInfos": [             // 适用的服务器信息
        {
          "version": "1.21.0.0",
          "name": "基岩版1.21",
          "description": ""
        }
    ],
    "requirements": [],                   // 前置插件
    "tags": [                             // 标签
        "entertainment",
        "management",
        "api",
        "development"
    ]
}
```
