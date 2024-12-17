---
title: Enum LoadOptions.PageSizeAdjustmentModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptionsPageSizeAdjustmentModes enum. ATTENTION The feature implemented but did not put yet to public API since blocker issue in OSHARED layer revealed for sample document. Represents mode of usage of page size during conversion. Formats like HTML EPUB etc usually have float design so it allows to fit required pagesize. But sometimes content has specifies horizontal positions or size that does not allow put content into required page size. In such case we can define what should be done in this case i.e when size of content does not fit required initial page size of result PDF document
type: docs
weight: 6070
url: /net/aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
## LoadOptions.PageSizeAdjustmentModes enumeration

ATTENTION! The feature implemented but did not put yet to public API since blocker issue in OSHARED layer revealed for sample document. Represents mode of usage of page size during conversion. Formats (like HTML, EPUB etc), usually have float design, so, it allows to fit required pagesize. But sometimes content has specifies horizontal positions or size that does not allow put content into required page size. In such case we can define what should be done in this case (i.e when size of content does not fit required initial page size of result PDF document).

```csharp
public enum PageSizeAdjustmentModes
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| NoAjustmentAllwaysUsePredefinedSize | `0` | In this mode result pages will have required pagesize defined in LoadOptions, no matter whether content after conversion goes out of page boundaries or no. |
| EnlargeRequiredViewportWidthAndDoConversionAgain | `1` | This mode defines such behaviour: after getting of conversion result , and detecting of fact that some content has been truncated, width of portview is enlarged to fit content and conversion is repeated. This mode allows getting of less pages in result in such case but requires repeated rendering(and therefore more processing time). |

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


