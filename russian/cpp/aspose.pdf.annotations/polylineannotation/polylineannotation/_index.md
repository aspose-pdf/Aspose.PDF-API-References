---
title: "Aspose::Pdf::Annotations::PolylineAnnotation::PolylineAnnotation конструктор"
linktitle: "PolylineAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::PolylineAnnotation::PolylineAnnotation конструктор. Создает новую аннотацию Polyline на указанной странице в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.annotations/polylineannotation/polylineannotation/
---
## PolylineAnnotation::PolylineAnnotation constructor


Создаёт новую аннотацию полилинии на указанной странице.

```cpp
Aspose::Pdf::Annotations::PolylineAnnotation::PolylineAnnotation(const System::SharedPtr<Aspose::Pdf::Page> &page, const System::SharedPtr<Rectangle> &rect, const System::ArrayPtr<System::SharedPtr<Point>> &vertices)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | const System::SharedPtr\<Aspose::Pdf::Page\>\& | Страница документа, где должна быть создана аннотация. |
| rect | const System::SharedPtr\<Rectangle\>\& | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| вершины | const System::ArrayPtr\<System::SharedPtr\<Point\>\>\& | Массив точек вершин полигона. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Rectangle](../../../aspose.pdf/rectangle/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Point](../../../aspose.pdf/point/)
* Class [PolylineAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
