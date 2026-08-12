---
title: "Конструктор Aspose::Pdf::Annotations::PolygonAnnotation::PolygonAnnotation"
linktitle: "PolygonAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Конструктор Aspose::Pdf::Annotations::PolygonAnnotation::PolygonAnnotation. Создаёт новую полигональную аннотацию на указанной странице в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.annotations/polygonannotation/polygonannotation/
---
## PolygonAnnotation::PolygonAnnotation(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::ArrayPtr\<System::SharedPtr\<Point\>\>\&) constructor


Создаёт новую полигональную аннотацию на указанной странице.

```cpp
Aspose::Pdf::Annotations::PolygonAnnotation::PolygonAnnotation(const System::SharedPtr<Aspose::Pdf::Page> &page, const System::SharedPtr<Rectangle> &rect, const System::ArrayPtr<System::SharedPtr<Point>> &vertices)
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
* Class [PolygonAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## PolygonAnnotation::PolygonAnnotation(const System::SharedPtr\<Document\>\&, const System::ArrayPtr\<System::SharedPtr\<Point\>\>\&) constructor


Конструктор для использования с Generator.

```cpp
Aspose::Pdf::Annotations::PolygonAnnotation::PolygonAnnotation(const System::SharedPtr<Document> &document, const System::ArrayPtr<System::SharedPtr<Point>> &vertices)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| document | const System::SharedPtr\<Document\>\& | [Document](../../../aspose.pdf/document/) где будет добавлена аннотация. |
| вершины | const System::ArrayPtr\<System::SharedPtr\<Point\>\>\& | Массив точек. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Point](../../../aspose.pdf/point/)
* Class [PolygonAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
