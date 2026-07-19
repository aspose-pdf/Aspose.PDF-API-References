---
title: "Aspose::Pdf::Annotations::TextAnnotation class"
linktitle: "TextAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::TextAnnotation class. Представляет текстовую аннотацию, которая является ''sticky note'', прикреплённой к точке в PDF‑документе на C++."
type: docs
weight: 11100
url: /ru/cpp/aspose.pdf.annotations/textannotation/
---
## TextAnnotation class


Представляет текстовую аннотацию, являющуюся «липкой заметкой», прикреплённой к точке в PDF‑документе.

```cpp
class TextAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Принимает объект‑посетитель для обработки аннотации. |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Переопределяет определение в базовом классе пустым телом. |
| [get_AnnotationType](./get_annotationtype/)() override | Получает тип аннотации. |
| [get_Icon](./get_icon/)() | Получает значок, используемый для отображения аннотации. |
| [get_Open](./get_open/)() | Получает флаг, указывающий, должна ли аннотация изначально отображаться открытой. |
| [set_Icon](./set_icon/)(TextIcon) | Устанавливает значок, используемый для отображения аннотации. |
| [set_Open](./set_open/)(bool) | Устанавливает флаг, указывающий, должна ли аннотация изначально отображаться открытой. |
| [TextAnnotation](./textannotation/)(const System::SharedPtr\<Document\>\&) | Конструктор аннотации, используемый в Generator. |
| [TextAnnotation](./textannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Создаёт новую аннотацию [Text](../../aspose.pdf.text/) на указанной странице. |
## См. также

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
