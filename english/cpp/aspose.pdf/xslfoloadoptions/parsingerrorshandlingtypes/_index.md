---
title: Aspose::Pdf::XslFoLoadOptions::ParsingErrorsHandlingTypes enum
linktitle: ParsingErrorsHandlingTypes
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::XslFoLoadOptions::ParsingErrorsHandlingTypes enum. Source XSLFO document can contain formatting errors. This enum enumerates possible strategies of handling of such formatting errors in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf/xslfoloadoptions/parsingerrorshandlingtypes/
---
## ParsingErrorsHandlingTypes enum


Source XSLFO document can contain formatting errors. This enum enumerates possible strategies of handling of such formatting errors.

```cpp
enum class ParsingErrorsHandlingTypes
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| TryIgnore | 0 | In this case converter will be instructed to try proceed with conversion and ignore found formatting errors. In this case success not guaranteed, serious problems can occure later in converter, anf in suck case will be thrown exception with list of found formatting errors. |
| ThrowExceptionImmediately | 1 | In this case conversion will be stopped immediately and exception will be thrown immediately after detecting of first formatting error. |
| InvokeCustomHandler | 2 | This is the most agile method - custom code must supply (in WarningCallback property) special handler that will be called when formatting error detected. That handler can f.e. log or count errors etc and will supply decision whether processing can be continued for this or that error. |

## See Also

* Class [XslFoLoadOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
