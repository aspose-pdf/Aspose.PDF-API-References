---
title: Aspose::Pdf::Annotations::InkAnnotation::InkAnnotation constructor
linktitle: InkAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::InkAnnotation::InkAnnotation constructor. Creates new Ink annotation on the specified page in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.annotations/inkannotation/inkannotation/
---
## InkAnnotation::InkAnnotation(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>\&) constructor


Creates new Ink annotation on the specified page.

```cpp
Aspose::Pdf::Annotations::InkAnnotation::InkAnnotation(const System::SharedPtr<Aspose::Pdf::Page> &page, const System::SharedPtr<Rectangle> &rect, const System::SharedPtr<System::Collections::Generic::IList<System::ArrayPtr<System::SharedPtr<Point>>>> &inkList)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | const System::SharedPtr\<Aspose::Pdf::Page\>\& | The document's page where annotation should be created. |
| rect | const System::SharedPtr\<Rectangle\>\& | The annotation rectangle, defining the location of the annotation on the page. |
| inkList | const System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>\& | An array of [Point](../../../aspose.pdf/point/)[] arrays, each representing a stroked path. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Rectangle](../../../aspose.pdf/rectangle/)
* Class [IList](../../../system.collections.generic/ilist/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Point](../../../aspose.pdf/point/)
* Class [InkAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## InkAnnotation::InkAnnotation(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>\&) constructor


Constructor for Ink annotation for Generator.

```cpp
Aspose::Pdf::Annotations::InkAnnotation::InkAnnotation(const System::SharedPtr<Document> &document, const System::SharedPtr<System::Collections::Generic::IList<System::ArrayPtr<System::SharedPtr<Point>>>> &inkList)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | const System::SharedPtr\<Document\>\& | [Document](../../../aspose.pdf/document/) where ink annotation will be created. |
| inkList | const System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>\& | An array of [Point](../../../aspose.pdf/point/)[] arrays, each representing a stroked path. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [IList](../../../system.collections.generic/ilist/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Point](../../../aspose.pdf/point/)
* Class [InkAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
