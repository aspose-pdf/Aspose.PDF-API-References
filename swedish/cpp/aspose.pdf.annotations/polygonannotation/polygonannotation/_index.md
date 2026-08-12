---
title: "Aspose::Pdf::Annotations::PolygonAnnotation::PolygonAnnotation konstruktor"
linktitle: "PolygonAnnotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::PolygonAnnotation::PolygonAnnotation konstruktor. Skapar en ny polygonannotering på den angivna sidan i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.annotations/polygonannotation/polygonannotation/
---
## PolygonAnnotation::PolygonAnnotation(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::ArrayPtr\<System::SharedPtr\<Point\>\>\&) constructor


Skapar ny Polygon-annotation på den angivna sidan.

```cpp
Aspose::Pdf::Annotations::PolygonAnnotation::PolygonAnnotation(const System::SharedPtr<Aspose::Pdf::Page> &page, const System::SharedPtr<Rectangle> &rect, const System::ArrayPtr<System::SharedPtr<Point>> &vertices)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | const System::SharedPtr\<Aspose::Pdf::Page\>\& | Dokumentets sida där annotationen ska skapas. |
| rect | const System::SharedPtr\<Rectangle\>\& | Annotationsrektangeln som definierar annotationens placering på sidan. |
| hörnpunkter | const System::ArrayPtr\<System::SharedPtr\<Point\>\>\& | En array av polygonens hörnpunkter. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Rectangle](../../../aspose.pdf/rectangle/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Point](../../../aspose.pdf/point/)
* Class [PolygonAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## PolygonAnnotation::PolygonAnnotation(const System::SharedPtr\<Document\>\&, const System::ArrayPtr\<System::SharedPtr\<Point\>\>\&) constructor


Konstruktor för användning med Generator.

```cpp
Aspose::Pdf::Annotations::PolygonAnnotation::PolygonAnnotation(const System::SharedPtr<Document> &document, const System::ArrayPtr<System::SharedPtr<Point>> &vertices)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | const System::SharedPtr\<Document\>\& | [Document](../../../aspose.pdf/document/) där annoteringen kommer att läggas till. |
| hörnpunkter | const System::ArrayPtr\<System::SharedPtr\<Point\>\>\& | Array av punkter. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Point](../../../aspose.pdf/point/)
* Class [PolygonAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
