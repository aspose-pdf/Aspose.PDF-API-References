---
title: "Aspose::Pdf::Annotations::LineAnnotation::LineAnnotation конструктор"
linktitle: "LineAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::LineAnnotation::LineAnnotation конструктор. Создаёт новую линейную аннотацию на указанной странице в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.annotations/lineannotation/lineannotation/
---
## LineAnnotation::LineAnnotation(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::SharedPtr\<Point\>\&, const System::SharedPtr\<Point\>\&) constructor


Создает новую аннотацию Line на указанной странице.

```cpp
Aspose::Pdf::Annotations::LineAnnotation::LineAnnotation(const System::SharedPtr<Aspose::Pdf::Page> &page, const System::SharedPtr<Rectangle> &rect, const System::SharedPtr<Point> &start, const System::SharedPtr<Point> &end)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | const System::SharedPtr\<Aspose::Pdf::Page\>\& | Страница документа, где должна быть создана аннотация. |
| rect | const System::SharedPtr\<Rectangle\>\& | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| начало | const System::SharedPtr\<Point\>\& | Точка, указывающая начальную координату линии. |
| end | const System::SharedPtr\<Point\>\& | Точка, указывающая конечную координату линии. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Rectangle](../../../aspose.pdf/rectangle/)
* Class [Point](../../../aspose.pdf/point/)
* Class [LineAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## LineAnnotation::LineAnnotation(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Point\>\&, const System::SharedPtr\<Point\>\&) constructor


Конструктор для использования с Generator.

```cpp
Aspose::Pdf::Annotations::LineAnnotation::LineAnnotation(const System::SharedPtr<Document> &document, const System::SharedPtr<Point> &start, const System::SharedPtr<Point> &end)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| document | const System::SharedPtr\<Document\>\& | [Документ](../../../aspose.pdf/document/) где будет создана аннотация. |
| начало | const System::SharedPtr\<Point\>\& | Начальная точка. |
| end | const System::SharedPtr\<Point\>\& | Конечная точка. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [Point](../../../aspose.pdf/point/)
* Class [LineAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
