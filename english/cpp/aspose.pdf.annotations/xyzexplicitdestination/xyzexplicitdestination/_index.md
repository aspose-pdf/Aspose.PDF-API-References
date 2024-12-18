---
title: Aspose::Pdf::Annotations::XYZExplicitDestination::XYZExplicitDestination constructor
linktitle: XYZExplicitDestination
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::XYZExplicitDestination::XYZExplicitDestination constructor. Creates remote explicit destination in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.annotations/xyzexplicitdestination/xyzexplicitdestination/
---
## XYZExplicitDestination::XYZExplicitDestination(int32_t, double, double, double) constructor


Creates remote explicit destination.

```cpp
Aspose::Pdf::Annotations::XYZExplicitDestination::XYZExplicitDestination(int32_t pageNumber, double left, double top, double zoom)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int32_t | The destination page number of remote document. |
| left | double | [Left](../../../aspose.pdf/left/) horizontal coordinate of the upper-left corner of the window. |
| top | double | Top vertical coordinate of the upper-left corner of the window. |
| zoom | double | Zoom factor. |

## See Also

* Class [XYZExplicitDestination](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## XYZExplicitDestination::XYZExplicitDestination(System::SharedPtr\<Aspose::Pdf::Page\>, double, double, double) constructor


Creates local explicit destination.

```cpp
Aspose::Pdf::Annotations::XYZExplicitDestination::XYZExplicitDestination(System::SharedPtr<Aspose::Pdf::Page> page, double left, double top, double zoom)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | System::SharedPtr\<Aspose::Pdf::Page\> | The destination page object. |
| left | double | [Left](../../../aspose.pdf/left/) horizontal coordinate of the upper-left corner of the window. |
| top | double | Top vertical coordinate of the upper-left corner of the window. |
| zoom | double | Zoom factor. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [XYZExplicitDestination](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## XYZExplicitDestination::XYZExplicitDestination(System::SharedPtr\<Document\>, int32_t, double, double, double) constructor


Creates remote explicit destination.

```cpp
Aspose::Pdf::Annotations::XYZExplicitDestination::XYZExplicitDestination(System::SharedPtr<Document> document, int32_t pageNumber, double left, double top, double zoom)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | System::SharedPtr\<Document\> | The parent document that contains this object. |
| pageNumber | int32_t | The destination page number of remote document. |
| left | double | [Left](../../../aspose.pdf/left/) horizontal coordinate of the upper-left corner of the window. |
| top | double | Top vertical coordinate of the upper-left corner of the window. |
| zoom | double | Zoom factor. |

## Deprecated
Use constructor without Document argument. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [XYZExplicitDestination](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
