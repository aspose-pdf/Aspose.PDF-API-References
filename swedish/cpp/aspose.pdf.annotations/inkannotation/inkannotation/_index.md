---
title: "Aspose::Pdf::Annotations::InkAnnotation::InkAnnotation konstruktor"
linktitle: "InkAnnotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::InkAnnotation::InkAnnotation konstruktor. Skapar en ny bläckanteckning på den angivna sidan i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.annotations/inkannotation/inkannotation/
---
## InkAnnotation::InkAnnotation(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>\&) constructor


Skapar en ny Ink-annotation på den angivna sidan.

```cpp
Aspose::Pdf::Annotations::InkAnnotation::InkAnnotation(const System::SharedPtr<Aspose::Pdf::Page> &page, const System::SharedPtr<Rectangle> &rect, const System::SharedPtr<System::Collections::Generic::IList<System::ArrayPtr<System::SharedPtr<Point>>>> &inkList)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | const System::SharedPtr\<Aspose::Pdf::Page\>\& | Dokumentets sida där annotationen ska skapas. |
| rect | const System::SharedPtr\<Rectangle\>\& | Annotationsrektangeln som definierar annotationens placering på sidan. |
| inkList | const System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>\& | En array av [Point](../../../aspose.pdf/point/)[]-arrayer, där varje representerar en ritad bana. |

## Se även

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


Konstruktor för Ink-annotation för Generator.

```cpp
Aspose::Pdf::Annotations::InkAnnotation::InkAnnotation(const System::SharedPtr<Document> &document, const System::SharedPtr<System::Collections::Generic::IList<System::ArrayPtr<System::SharedPtr<Point>>>> &inkList)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | const System::SharedPtr\<Document\>\& | [Document](../../../aspose.pdf/document/) där bläckanteckningen kommer att skapas. |
| inkList | const System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>\& | En array av [Point](../../../aspose.pdf/point/)[]-arrayer, där varje representerar en ritad bana. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [IList](../../../system.collections.generic/ilist/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Point](../../../aspose.pdf/point/)
* Class [InkAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
