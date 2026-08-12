---
title: "Aspose::Pdf::Annotations::PolylineAnnotation::PolylineAnnotation constructor"
linktitle: "PolylineAnnotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::PolylineAnnotation::PolylineAnnotation constructor. Skapar en ny Polyline-annotation på den angivna sidan i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.annotations/polylineannotation/polylineannotation/
---
## PolylineAnnotation::PolylineAnnotation constructor


Skapar en ny polylinjeanteckning på den angivna sidan.

```cpp
Aspose::Pdf::Annotations::PolylineAnnotation::PolylineAnnotation(const System::SharedPtr<Aspose::Pdf::Page> &page, const System::SharedPtr<Rectangle> &rect, const System::ArrayPtr<System::SharedPtr<Point>> &vertices)
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
* Class [PolylineAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
