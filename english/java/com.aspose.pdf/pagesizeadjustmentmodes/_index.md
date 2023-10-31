---
title: LoadOptions.PageSizeAdjustmentModes
second_title: Aspose.PDF for Java API Reference
description: ATTENTION The feature implemented but did not put yet to public API since blocker issue in OSHARED layer revealed for sample document.
type: docs
weight: 11
url: /java/com.aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public static final class LoadOptions.PageSizeAdjustmentModes extends System.Enum
```

ATTENTION! The feature implemented but did not put yet to public API since blocker issue in OSHARED layer revealed for sample document. Represents mode of usage of page size during conversion. Formats (like HTML, EPUB etc), usually have float design, so, it allows to fit required pagesize. But sometimes content has specifies horizontal positions or size that does not allow put content into required page size. In such case we can define what should be done in this case (i.e when size of content does not fit required initial page size of result PDF document).
## Fields

| Field | Description |
| --- | --- |
| [NoAjustmentAllwaysUsePredefinedSize](#NoAjustmentAllwaysUsePredefinedSize) | In this mode result pages will have required pagesize defined in LoadOptions, no matter whether content after conversion goes out of page boundaries or no. |
| [EnlargeRequiredViewportWidthAndDoConversionAgain](#EnlargeRequiredViewportWidthAndDoConversionAgain) | This mode defines such behaviour: after getting of conversion result , and detecting of fact that some content has been truncated, width of portview is enlarged to fit content and conversion is repeated. |
### NoAjustmentAllwaysUsePredefinedSize {#NoAjustmentAllwaysUsePredefinedSize}
```
public static final int NoAjustmentAllwaysUsePredefinedSize
```


In this mode result pages will have required pagesize defined in LoadOptions, no matter whether content after conversion goes out of page boundaries or no.

### EnlargeRequiredViewportWidthAndDoConversionAgain {#EnlargeRequiredViewportWidthAndDoConversionAgain}
```
public static final int EnlargeRequiredViewportWidthAndDoConversionAgain
```


This mode defines such behaviour: after getting of conversion result , and detecting of fact that some content has been truncated, width of portview is enlarged to fit content and conversion is repeated. This mode allows getting of less pages in result in such case but requires repeated rendering(and therefore more processing time).

