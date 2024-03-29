---
title: XslFoLoadOptions.ParsingErrorsHandlingTypes
second_title: Aspose.PDF for .NET API 参考
description: 源 XSLFO 文档可能包含格式错误这个枚举列举了处理这种格式错误的可能策略
type: docs
weight: 7590
url: /zh/net/aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
## XslFoLoadOptions.ParsingErrorsHandlingTypes enumeration

源 XSLFO 文档可能包含格式错误。这个枚举列举了处理这种格式错误的可能策略

```csharp
public enum ParsingErrorsHandlingTypes
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| TryIgnore | `0` | 在这种情况下，转换器将被指示尝试进行 转换并忽略发现的格式错误。 在这种情况下，不能保证成功， 稍后可能会在转换器中出现严重问题， anf in sink case 将抛出异常并列出 found 格式错误. |
| ThrowExceptionImmediately | `1` | 这种情况下会立即停止转换 并在检测到第一次格式化错误 后立即抛出异常 |
| InvokeCustomHandler | `2` | 这是最灵活的方法 - 自定义代码必须提供（在 WarningCallback 属性中）special 处理程序，当检测到格式化错误时将调用该处理程序。 该处理程序可以记录或计数错误等， 将决定是否可以继续处理这个或那个错误。 |

### 也可以看看

* class [XslFoLoadOptions](../xslfoloadoptions)
* 命名空间 [Aspose.Pdf](../../aspose.pdf)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
