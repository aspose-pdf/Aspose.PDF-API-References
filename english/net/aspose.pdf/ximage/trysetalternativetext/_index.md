---
title: "XImage.TrySetAlternativeText"
linktitle: "TrySetAlternativeText"
articleTitle: "TrySetAlternativeText"
second_title: "Aspose.PDF for .NET API Reference"
description: "XImage method. Sets alternative text for an XImage on the page."
type: docs
weight: 140
url: "/net/aspose.pdf/ximage/trysetalternativetext/"
product_version: "26.9.0"
---
## TrySetAlternativeText(string, [Page](../../../aspose.pdf/page/)) {#trysetalternativetext}

Sets alternative text for an XImage on the page.

The method returns false in the following cases:
 - The XImage is not found on the specified page.
 - The XImage appears multiple times on the page with different structural elements, 
 making it ambiguous which instance should receive the alternative text.

```csharp
public bool TrySetAlternativeText(string alternativeText, Page page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| alternativeText | string | The alternative text to be specified. |
| page | Page | Page where XImage is located. |

### Return Value

bool

True if alternativeText for XImage is set. False if alternativeText for XImage not set.

### See Also

* class [XImage](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

