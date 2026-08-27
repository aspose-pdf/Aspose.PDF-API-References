---
title: "枚举 XslFoLoadOptions.ParsingErrorsHandlingTypes"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.XslFoLoadOptionsParsingErrorsHandlingTypes 枚举。源 XSLFO 文档可能包含格式错误。此枚举列举了处理此类格式错误的可能策略"
type: docs
weight: 11730
url: /zh/net/aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
## XslFoLoadOptions.ParsingErrorsHandlingTypes enumeration

源 XSLFO 文档可能包含格式错误。此枚举列举了处理此类格式错误的可能策略

```csharp
public enum ParsingErrorsHandlingTypes
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| TryIgnore | `0` | 在这种情况下，转换器将被指示尝试继续转换并忽略发现的格式错误。此时成功无法保证，转换器后续可能出现严重问题，并且在这种情况下将抛出包含发现的格式错误列表的异常。 |
| ThrowExceptionImmediately | `1` | 在这种情况下，转换将在检测到第一个格式错误后立即停止，并立即抛出异常。 |
| InvokeCustomHandler | `2` | 这是最灵活的方法——自定义代码必须在 WarningCallback 属性中提供一个特殊处理程序，该处理程序将在检测到格式错误时被调用。该处理程序例如可以记录或计数错误等，并提供是否可以继续处理该错误的决定。 |

### 另请参见

* class [XslFoLoadOptions](../xslfoloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


