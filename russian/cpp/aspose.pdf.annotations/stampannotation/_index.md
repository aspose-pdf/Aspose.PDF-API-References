---
title: "Aspose::Pdf::Annotations::StampAnnotation class"
linktitle: "StampAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::StampAnnotation class. Представляет аннотацию в виде резиновой печати. Этот тип аннотации отображает текст или графику, имитирующую печать на странице резиновой печатью в C++."
type: docs
weight: 10700
url: /ru/cpp/aspose.pdf.annotations/stampannotation/
---
## StampAnnotation class


Представляет аннотацию в виде резиновой печати. Этот тип аннотации отображает текст или графику, имитирующие печать на странице резиновой печатью.

```cpp
class StampAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Принимает [AnnotationSelector](../annotationselector/) посетителя при обходе коллекции аннотаций. |
| [get_AnnotationType](./get_annotationtype/)() override | Получает тип аннотации. |
| [get_Icon](./get_icon/)() | Получает значок для резиновой печати. |
| [get_Image](./get_image/)() | Получает изображение аннотации. |
| [set_Icon](./set_icon/)(StampIcon) | Устанавливает значок для резиновой печати. |
| [set_Image](./set_image/)(const System::SharedPtr\<System::IO::Stream\>\&) | Устанавливает изображение аннотации. |
| [StampAnnotation](./stampannotation/)(const System::SharedPtr\<Document\>\&) | Конструктор. |
| [StampAnnotation](./stampannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Создаёт новую аннотацию [Stamp](../../aspose.pdf/stamp/) на указанной странице. |
## См. также

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
