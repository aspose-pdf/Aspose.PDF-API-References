---
title: "Конструктор Aspose::Pdf::Annotations::InkAnnotation::InkAnnotation"
linktitle: "InkAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Конструктор Aspose::Pdf::Annotations::InkAnnotation::InkAnnotation. Создает новую чернильную аннотацию на указанной странице в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.annotations/inkannotation/inkannotation/
---
## InkAnnotation::InkAnnotation(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>\&) constructor


Создаёт новую аннотацию Ink на указанной странице.

```cpp
Aspose::Pdf::Annotations::InkAnnotation::InkAnnotation(const System::SharedPtr<Aspose::Pdf::Page> &page, const System::SharedPtr<Rectangle> &rect, const System::SharedPtr<System::Collections::Generic::IList<System::ArrayPtr<System::SharedPtr<Point>>>> &inkList)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | const System::SharedPtr\<Aspose::Pdf::Page\>\& | Страница документа, где должна быть создана аннотация. |
| rect | const System::SharedPtr\<Rectangle\>\& | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| inkList | const System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>\& | Массив массивов [Point](../../../aspose.pdf/point/)[], каждый представляющий нарисованный путь. |

## См. также

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


Конструктор аннотации Ink для Generator.

```cpp
Aspose::Pdf::Annotations::InkAnnotation::InkAnnotation(const System::SharedPtr<Document> &document, const System::SharedPtr<System::Collections::Generic::IList<System::ArrayPtr<System::SharedPtr<Point>>>> &inkList)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| document | const System::SharedPtr\<Document\>\& | [Document](../../../aspose.pdf/document/) где будет создана чернильная аннотация. |
| inkList | const System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>\& | Массив массивов [Point](../../../aspose.pdf/point/)[], каждый представляющий нарисованный путь. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [IList](../../../system.collections.generic/ilist/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Point](../../../aspose.pdf/point/)
* Class [InkAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
