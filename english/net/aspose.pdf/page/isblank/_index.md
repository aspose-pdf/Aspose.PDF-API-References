---
title: Page.IsBlank
second_title: Aspose.PDF for .NET API Reference
description: Page method. Gets the flag whether page is blank or not
type: docs
weight: 490
url: /net/aspose.pdf/page/isblank/
---
## Page.IsBlank method

Gets the flag whether page is blank or not.

```csharp
public bool IsBlank(double fillThresholdFactor)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fillThresholdFactor | Double | The fill threshold value that manages the sensitivity of detection. Should be in range [0..1). |

### Return Value

True - if page is blank; otherwise, false.

## Remarks

To determine whether a page is empty or not, the ratio of the filled space to the total space of the page is calculated. This ratio is compared with the fillThresholdFactor parameter and if it is less, the page is considered empty.

### See Also

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


