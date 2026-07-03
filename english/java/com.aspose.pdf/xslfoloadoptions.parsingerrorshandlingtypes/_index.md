---
title: XslFoLoadOptions.ParsingErrorsHandlingTypes
second_title: Aspose.PDF for Java API Reference
description: Source XSLFO document can contain formatting errors. This enum enumerates possible strategies of handling of such formatting errors
type: docs
weight: 5790
url: /java/com.aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.Enum, com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes

```
public static final class XslFoLoadOptions.ParsingErrorsHandlingTypes extends com.aspose.ms.System.Enum
```

Source XSLFO document can contain formatting errors. This enum enumerates possible strategies of handling of such formatting errors

## Fields

| Field | Description |
| --- | --- |
| [InvokeCustomHandler](#InvokeCustomHandler) | This is the most agile method - custom code must supply (in WarningCallback property) special handler that will be called when formatting error detected. That handler can f.e. log or count errors etc and will supply decision whether processing can be continued for this or that error. |
| [ThrowExceptionImmediately](#ThrowExceptionImmediately) | In this case conversion will be stopped immediately and exception will be thrown immediately after detecting of first formatting error |
| [TryIgnore](#TryIgnore) | In this case converter will be instructed to try proceed with conversion and ignore found formatting errors. In this case success not guaranteed, serious problems can occure later in converter, anf in suck case will be thrown exception with list of found formatting errors. |

### InvokeCustomHandler {#InvokeCustomHandler}
```
public static final int InvokeCustomHandler
```

This is the most agile method - custom code must supply (in WarningCallback property) special handler that will be called when formatting error detected. That handler can f.e. log or count errors etc and will supply decision whether processing can be continued for this or that error.

### ThrowExceptionImmediately {#ThrowExceptionImmediately}
```
public static final int ThrowExceptionImmediately
```

In this case conversion will be stopped immediately and exception will be thrown immediately after detecting of first formatting error

### TryIgnore {#TryIgnore}
```
public static final int TryIgnore
```

In this case converter will be instructed to try proceed with conversion and ignore found formatting errors. In this case success not guaranteed, serious problems can occure later in converter, anf in suck case will be thrown exception with list of found formatting errors.
