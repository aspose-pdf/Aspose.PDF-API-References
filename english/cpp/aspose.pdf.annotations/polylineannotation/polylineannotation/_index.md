---
title: Aspose::Pdf::Annotations::PolylineAnnotation::PolylineAnnotation constructor
linktitle: PolylineAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::PolylineAnnotation::PolylineAnnotation constructor. Creates new Polyline annotation on the specified page in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.annotations/polylineannotation/polylineannotation/
---
## PolylineAnnotation::PolylineAnnotation constructor


Creates new Polyline annotation on the specified page.

```cpp
Aspose::Pdf::Annotations::PolylineAnnotation::PolylineAnnotation(const System::SharedPtr<Aspose::Pdf::Page> &page, const System::SharedPtr<Rectangle> &rect, const System::ArrayPtr<System::SharedPtr<Point>> &vertices)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | const System::SharedPtr\<Aspose::Pdf::Page\>\& | The document's page where annotation should be created. |
| rect | const System::SharedPtr\<Rectangle\>\& | The annotation rectangle, defining the location of the annotation on the page. |
| vertices | const System::ArrayPtr\<System::SharedPtr\<Point\>\>\& | An array of polygon vertices points. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Rectangle](../../../aspose.pdf/rectangle/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Point](../../../aspose.pdf/point/)
* Class [PolylineAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
