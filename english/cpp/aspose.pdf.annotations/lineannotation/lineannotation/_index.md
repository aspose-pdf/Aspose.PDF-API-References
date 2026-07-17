---
title: Aspose::Pdf::Annotations::LineAnnotation::LineAnnotation constructor
linktitle: LineAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::LineAnnotation::LineAnnotation constructor. Creates new Line annotation on the specified page in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.annotations/lineannotation/lineannotation/
---
## LineAnnotation::LineAnnotation(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::SharedPtr\<Point\>\&, const System::SharedPtr\<Point\>\&) constructor


Creates new Line annotation on the specified page.

```cpp
Aspose::Pdf::Annotations::LineAnnotation::LineAnnotation(const System::SharedPtr<Aspose::Pdf::Page> &page, const System::SharedPtr<Rectangle> &rect, const System::SharedPtr<Point> &start, const System::SharedPtr<Point> &end)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | const System::SharedPtr\<Aspose::Pdf::Page\>\& | The document's page where annotation should be created. |
| rect | const System::SharedPtr\<Rectangle\>\& | The annotation rectangle, defining the location of the annotation on the page. |
| start | const System::SharedPtr\<Point\>\& | A point, specifying the starting coordinate of the line. |
| end | const System::SharedPtr\<Point\>\& | A point, specifying the ending coordinate of the line. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Rectangle](../../../aspose.pdf/rectangle/)
* Class [Point](../../../aspose.pdf/point/)
* Class [LineAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## LineAnnotation::LineAnnotation(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Point\>\&, const System::SharedPtr\<Point\>\&) constructor


Constructor for using with Generator.

```cpp
Aspose::Pdf::Annotations::LineAnnotation::LineAnnotation(const System::SharedPtr<Document> &document, const System::SharedPtr<Point> &start, const System::SharedPtr<Point> &end)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | const System::SharedPtr\<Document\>\& | [Document](../../../aspose.pdf/document/) where annotation will be created. |
| start | const System::SharedPtr\<Point\>\& | Starting point. |
| end | const System::SharedPtr\<Point\>\& | Ending point. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [Point](../../../aspose.pdf/point/)
* Class [LineAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
