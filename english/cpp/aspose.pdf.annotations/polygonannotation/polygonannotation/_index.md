---
title: Aspose::Pdf::Annotations::PolygonAnnotation::PolygonAnnotation constructor
linktitle: PolygonAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::PolygonAnnotation::PolygonAnnotation constructor. Creates new Polygon annotation on the specified page in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.annotations/polygonannotation/polygonannotation/
---
## PolygonAnnotation::PolygonAnnotation(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::ArrayPtr\<System::SharedPtr\<Point\>\>\&) constructor


Creates new Polygon annotation on the specified page.

```cpp
Aspose::Pdf::Annotations::PolygonAnnotation::PolygonAnnotation(const System::SharedPtr<Aspose::Pdf::Page> &page, const System::SharedPtr<Rectangle> &rect, const System::ArrayPtr<System::SharedPtr<Point>> &vertices)
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
* Class [PolygonAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## PolygonAnnotation::PolygonAnnotation(const System::SharedPtr\<Document\>\&, const System::ArrayPtr\<System::SharedPtr\<Point\>\>\&) constructor


Constructor for using with Generator.

```cpp
Aspose::Pdf::Annotations::PolygonAnnotation::PolygonAnnotation(const System::SharedPtr<Document> &document, const System::ArrayPtr<System::SharedPtr<Point>> &vertices)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | const System::SharedPtr\<Document\>\& | [Document](../../../aspose.pdf/document/) where annotation will be added. |
| vertices | const System::ArrayPtr\<System::SharedPtr\<Point\>\>\& | Array of points. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Point](../../../aspose.pdf/point/)
* Class [PolygonAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
