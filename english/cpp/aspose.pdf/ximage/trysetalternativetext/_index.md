---
title: Aspose::Pdf::XImage::TrySetAlternativeText method
linktitle: TrySetAlternativeText
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::XImage::TrySetAlternativeText method. Sets alternative text for an XImage on the page in C++.'
type: docs
weight: 1900
url: /cpp/aspose.pdf/ximage/trysetalternativetext/
---
## XImage::TrySetAlternativeText method


Sets alternative text for an [XImage](../) on the page.

```cpp
bool Aspose::Pdf::XImage::TrySetAlternativeText(System::String alternativeText, System::SharedPtr<Aspose::Pdf::Page> page)
```


| Parameter | Type | Description |
| --- | --- | --- |
| alternativeText | System::String | The alternative text to be specified. |
| page | System::SharedPtr\<Aspose::Pdf::Page\> | [Page](../../page/) where [XImage](../) is located. |

### ReturnValue

True if alternativeText for [XImage](../) is set. False if alternativeText for [XImage](../) not set.
## Remarks



The method returns false in the following cases:* The [XImage](../) is not found on the specified page.
* The [XImage](../) appears multiple times on the page with different structural elements, making it ambiguous which instance should receive the alternative text.


## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [XImage](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
