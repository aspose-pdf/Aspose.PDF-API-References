---
title: "XslFoLoadOptions.ParsingErrorsHandlingTypes"
linktitle: "XslFoLoadOptions.ParsingErrorsHandlingTypes"
second_title: "Aspose.PDF for Java API 参考"
description: "源 XSLFO 文档可能包含格式错误。此枚举列举了处理此类格式错误的可能策略。"
type: docs
weight: 5790
url: /zh/java/com.aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.Enum, com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes

```
public static final class XslFoLoadOptions.ParsingErrorsHandlingTypes extends com.aspose.ms.System.Enum
```

源 XSLFO 文档可能包含格式错误。此枚举列举了处理此类格式错误的可能策略。

## 字段

| 字段 | 描述 |
| --- | --- |
| [InvokeCustomHandler](#InvokeCustomHandler) | 这是最灵活的方法——自定义代码必须在 WarningCallback 属性中提供一个特殊处理程序，该处理程序将在检测到格式错误时被调用。该处理程序可以例如记录或统计错误等，并决定是否可以继续处理此错误或该错误。 |
| [ThrowExceptionImmediately](#ThrowExceptionImmediately) | 在这种情况下，转换将在检测到第一个格式错误后立即停止，并立即抛出异常。 |
| [TryIgnore](#TryIgnore) | 在这种情况下，转换器将被指示尝试继续转换并忽略已发现的格式错误。但成功无法保证，转换器后续可能会出现严重问题；在这种情况下将抛出包含已发现格式错误列表的异常。 |

### InvokeCustomHandler {#InvokeCustomHandler}
```
public static final int InvokeCustomHandler
```

这是最灵活的方法——自定义代码必须在 WarningCallback 属性中提供一个特殊处理程序，该处理程序将在检测到格式错误时被调用。该处理程序可以例如记录或统计错误等，并决定是否可以继续处理此错误或该错误。

### ThrowExceptionImmediately {#ThrowExceptionImmediately}
```
public static final int ThrowExceptionImmediately
```

在这种情况下，转换将在检测到第一个格式错误后立即停止，并立即抛出异常。

### TryIgnore {#TryIgnore}
```
public static final int TryIgnore
```

在这种情况下，转换器将被指示尝试继续转换并忽略已发现的格式错误。但成功无法保证，转换器后续可能会出现严重问题；在这种情况下将抛出包含已发现格式错误列表的异常。
