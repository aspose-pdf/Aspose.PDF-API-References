---
title: Aspose::Pdf::Annotations::XYZExplicitDestination::CreateDestination method
linktitle: CreateDestination
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::XYZExplicitDestination::CreateDestination method. Create destintion to specified location of the page considering page rotation if required in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf.annotations/xyzexplicitdestination/createdestination/
---
## XYZExplicitDestination::CreateDestination method


Create destintion to specified location of the page considering page rotation if required.

```cpp
static System::SharedPtr<XYZExplicitDestination> Aspose::Pdf::Annotations::XYZExplicitDestination::CreateDestination(System::SharedPtr<Aspose::Pdf::Page> page, double left, double top, double zoom, bool considerRotation)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | System::SharedPtr\<Aspose::Pdf::Page\> | Destination page. |
| left | double | [Left](../../../aspose.pdf/left/) position on the page. |
| top | double | Top position on the page. |
| zoom | double | Zoom factor (0 for default). |
| considerRotation | bool | If true position will be recalculated according to page rotation. |

### ReturnValue

Destination object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XYZExplicitDestination](../)
* Class [Page](../../../aspose.pdf/page/)
* Class [XYZExplicitDestination](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
