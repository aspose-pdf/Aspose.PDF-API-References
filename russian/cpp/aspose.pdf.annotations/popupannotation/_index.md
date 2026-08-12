---
title: "Aspose::Pdf::Annotations::PopupAnnotation class"
linktitle: "PopupAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::PopupAnnotation class. Представляет всплывающую аннотацию, которая отображает текст во всплывающем окне для ввода и редактирования в C++."
type: docs
weight: 8800
url: /ru/cpp/aspose.pdf.annotations/popupannotation/
---
## PopupAnnotation class


Представляет всплывающую аннотацию, которая отображает текст во всплывающем окне для ввода и редактирования.

```cpp
class PopupAnnotation : public Aspose::Pdf::Annotations::Annotation
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Принимает объект‑посетитель для обработки аннотации. |
| [get_AnnotationType](./get_annotationtype/)() override | Получает тип аннотации. |
| [get_Open](./get_open/)() | Возвращает флаг, указывающий, должна ли всплывающая аннотация изначально отображаться открытой. |
| [get_Parent](./get_parent/)() | Возвращает родительскую аннотацию, с которой должна быть связана эта всплывающая аннотация. Если эта запись присутствует, записи Contents, M, C и T родительской аннотации переопределяют соответствующие записи самой всплывающей аннотации. |
| [PopupAnnotation](./popupannotation/)(const System::SharedPtr\<Document\>\&) | Конструктор для использования в Generator. |
| [PopupAnnotation](./popupannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Создаёт новую всплывающую аннотацию на указанной странице. |
| [set_Open](./set_open/)(bool) | Устанавливает флаг, указывающий, должна ли всплывающая аннотация изначально отображаться открытой. |
| [set_Parent](./set_parent/)(const System::SharedPtr\<Annotation\>\&) | Устанавливает родительскую аннотацию, с которой должна быть связана эта всплывающая аннотация. Если эта запись присутствует, записи Contents, M, C и T родительской аннотации переопределяют соответствующие записи самой всплывающей аннотации. |
## См. также

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
