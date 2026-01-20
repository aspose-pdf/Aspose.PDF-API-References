---
title: Aspose::Pdf::Page::IsBlank method
linktitle: IsBlank
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Page::IsBlank method. Gets the flag whether page is blank or not in C++.'
type: docs
weight: 4800
url: /cpp/aspose.pdf/page/isblank/
---
## Page::IsBlank method


Gets the flag whether page is blank or not.

```cpp
bool Aspose::Pdf::Page::IsBlank(double fillThresholdFactor)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fillThresholdFactor | double | The fill threshold value that manages the sensitivity of detection. Should be in range [0..1). |

### ReturnValue

True - if page is blank; otherwise, false.
## Remarks



To determine whether a page is empty or not, the ratio of the filled space to the total space of the page is calculated. This ratio is compared with the fillThresholdFactor parameter and if it is less, the page is considered empty. 
## See Also

* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
