---
title: Enum HtmlSaveOptions.FontEncodingRules
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsFontEncodingRules enum. This enumeration defines rules which tune encoding logic
type: docs
weight: 3970
url: /net/aspose.pdf/htmlsaveoptions.fontencodingrules/
---
## HtmlSaveOptions.FontEncodingRules enumeration

This enumeration defines rules which tune encoding logic

```csharp
public enum FontEncodingRules : byte
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Default | `0` | Leave encoding logic "as is" - in accordance with PDF specification |
| DecreaseToUnicodePriorityLevel | `1` | ToUnicode is a special mechanism which helps to decode input codes to unicode symbols. According to specification it must be used first of all mechanisms to get unicode symbols for specific input code. But some documents has non-standard fonts and to convert these documents correctly it may be necessary to decrease ToUnicode priority and use another mechanisms to decode input codes. |

### See Also

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


