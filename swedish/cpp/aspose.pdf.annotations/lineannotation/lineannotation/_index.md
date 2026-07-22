---
title: "Aspose::Pdf::Annotations::LineAnnotation::LineAnnotation konstruktor"
linktitle: "LineAnnotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::LineAnnotation::LineAnnotation konstruktor. Skapar en ny linjeannotation på den angivna sidan i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.annotations/lineannotation/lineannotation/
---
## LineAnnotation::LineAnnotation(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::SharedPtr\<Point\>\&, const System::SharedPtr\<Point\>\&) constructor


Skapar ny linjeannotation på den angivna sidan.

```cpp
Aspose::Pdf::Annotations::LineAnnotation::LineAnnotation(const System::SharedPtr<Aspose::Pdf::Page> &page, const System::SharedPtr<Rectangle> &rect, const System::SharedPtr<Point> &start, const System::SharedPtr<Point> &end)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | const System::SharedPtr\<Aspose::Pdf::Page\>\& | Dokumentets sida där annotationen ska skapas. |
| rect | const System::SharedPtr\<Rectangle\>\& | Annotationsrektangeln som definierar annotationens placering på sidan. |
| start | const System::SharedPtr\<Point\>\& | En punkt som specificerar startkoordinaten för linjen. |
| end | const System::SharedPtr\<Point\>\& | En punkt som specificerar slutkoordinaten för linjen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Rectangle](../../../aspose.pdf/rectangle/)
* Class [Point](../../../aspose.pdf/point/)
* Class [LineAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## LineAnnotation::LineAnnotation(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Point\>\&, const System::SharedPtr\<Point\>\&) constructor


Konstruktor för användning med Generator.

```cpp
Aspose::Pdf::Annotations::LineAnnotation::LineAnnotation(const System::SharedPtr<Document> &document, const System::SharedPtr<Point> &start, const System::SharedPtr<Point> &end)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | const System::SharedPtr\<Document\>\& | [Document](../../../aspose.pdf/document/) där annotationen kommer att skapas. |
| start | const System::SharedPtr\<Point\>\& | Startpunkt. |
| end | const System::SharedPtr\<Point\>\& | Slutpunkt. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [Point](../../../aspose.pdf/point/)
* Class [LineAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
