---
title: "Aspose::Pdf::Annotations::InkAnnotation class"
linktitle: "InkAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::InkAnnotation class. Представляет свободную \\\"карандашную\\\" запись, состоящую из одного или нескольких разрозненных путей в C++."
type: docs
weight: 5200
url: /ru/cpp/aspose.pdf.annotations/inkannotation/
---
## InkAnnotation class


Представляет свободный "scribble", состоящий из одной или нескольких разрозненных путей.

```cpp
class InkAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Принимает объект‑посетитель для обработки аннотации. |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Обновляет точки в InkList в соответствии с преобразованием матрицы. |
| [get_AnnotationType](./get_annotationtype/)() override | Получает тип аннотации. |
| [get_CapStyle](./get_capstyle/)() | Стиль окончаний линий аннотации чернила. |
| [get_InkList](./get_inklist/)() | Получает список жестов, которые являются независимыми линиями и представлены массивами [Point](../../aspose.pdf/point/)[] . |
| [InkAnnotation](./inkannotation/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>\&) | Конструктор аннотации Ink для Generator. |
| [InkAnnotation](./inkannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>\&) | Создаёт новую аннотацию Ink на указанной странице. |
| [set_CapStyle](./set_capstyle/)(Aspose::Pdf::Annotations::CapStyle) | Стиль окончаний линий аннотации чернила. |
| [set_InkList](./set_inklist/)(const System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>\&) | Устанавливает список жестов, представляющих независимые линии, представленные массивами [Point](../../aspose.pdf/point/)[] . |
## См. также

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
