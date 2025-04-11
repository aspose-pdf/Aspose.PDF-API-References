---
title: Enum XslFoLoadOptions.ParsingErrorsHandlingTypes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XslFoLoadOptionsParsingErrorsHandlingTypes 枚举。源 XSLFO 文档可能包含格式错误。此枚举列举了处理此类格式错误的可能策略
type: docs
weight: 11540
url: /zh/net/aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
## XslFoLoadOptions.ParsingErrorsHandlingTypes 枚举

源 XSLFO 文档可能包含格式错误。此枚举列举了处理此类格式错误的可能策略

```csharp
public enum ParsingErrorsHandlingTypes
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| TryIgnore | `0` | 在这种情况下，转换器将被指示尝试继续转换并忽略发现的格式错误。在这种情况下，成功无法保证，转换器可能会在后续出现严重问题，并且在这种情况下将抛出包含发现的格式错误列表的异常。 |
| ThrowExceptionImmediately | `1` | 在这种情况下，转换将在检测到第一个格式错误后立即停止，并立即抛出异常。 |
| InvokeCustomHandler | `2` | 这是最灵活的方法 - 自定义代码必须在 WarningCallback 属性中提供特殊处理程序，当检测到格式错误时将被调用。该处理程序可以例如记录或计数错误等，并将提供是否可以继续处理此或那种错误的决策。 |

### 另请参阅

* 类 [XslFoLoadOptions](../xslfoloadoptions/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)