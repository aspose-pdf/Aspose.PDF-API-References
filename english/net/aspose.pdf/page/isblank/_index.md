---
title: "Page.IsBlank"
linktitle: "IsBlank"
articleTitle: "IsBlank"
second_title: "Aspose.PDF for .NET"
description: "Gets the flag whether page is blank or not."
type: docs
weight: 80
url: "/net/aspose.pdf/page/isblank/"
product_version: "26.9.0"
---
## IsBlank(double) {#isblank}

Gets the flag whether page is blank or not.

To determine whether a page is empty or not, the ratio of the filled space to the total space of the page is calculated.
 This ratio is compared with the fillThresholdFactor parameter and if it is less, the page is considered empty.

```csharp
public bool IsBlank(double fillThresholdFactor)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fillThresholdFactor | double | The fill threshold value that manages the sensitivity of detection. Should be in range [0..1). |

### Return Value

bool

True - if page is blank; otherwise, false.

### See Also

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

