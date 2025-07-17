---
title: XImage.TrySetAlternativeText
second_title: Aspose.PDF for .NET API Reference
description: XImage method. Sets alternative text for an XImage on the page
type: docs
weight: 180
url: /net/aspose.pdf/ximage/trysetalternativetext/
---
## XImage.TrySetAlternativeText method

Sets alternative text for an XImage on the page.

```csharp
public bool TrySetAlternativeText(string alternativeText, Page page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| alternativeText | String | The alternative text to be specified. |
| page | Page | Page where XImage is located. |

### Return Value

True if alternativeText for XImage is set. False if alternativeText for XImage not set.

## Remarks

The method returns false in the following cases: - The XImage is not found on the specified page. - The XImage appears multiple times on the page with different structural elements, making it ambiguous which instance should receive the alternative text.

### See Also

* class [Page](../../page/)
* class [XImage](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


