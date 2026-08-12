---
title: "Aspose::Pdf::Annotations::CaretAnnotation класс"
linktitle: "CaretAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::CaretAnnotation класс. Класс, представляющий аннотацию Caret в C++."
type: docs
weight: 1500
url: /ru/cpp/aspose.pdf.annotations/caretannotation/
---
## CaretAnnotation class


Класс, представляющий аннотацию Caret.

```cpp
class CaretAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Принимает объект‑посетитель для обработки аннотации. |
| [CaretAnnotation](./caretannotation/)(const System::SharedPtr\<Document\>\&) | Конструктор для использования в Generator. |
| [CaretAnnotation](./caretannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Создаёт новую аннотацию Caret на указанной странице. |
| [get_AnnotationType](./get_annotationtype/)() override | Получает тип аннотации. |
| [get_Frame](./get_frame/)() | Получает прямоугольник caret. |
| [get_Symbol](./get_symbol/)() | Получает символ, связанный с caret. |
| [set_Frame](./set_frame/)(const System::SharedPtr\<Rectangle\>\&) | Устанавливает прямоугольник caret. |
| [set_Symbol](./set_symbol/)(CaretSymbol) | Устанавливает символ, связанный с caret. |
## См. также

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
