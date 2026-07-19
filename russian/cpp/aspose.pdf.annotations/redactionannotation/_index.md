---
title: "Aspose::Pdf::Annotations::RedactionAnnotation класс"
linktitle: "RedactionAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::RedactionAnnotation класс. Представляет аннотацию Redact в C++."
type: docs
weight: 9200
url: /ru/cpp/aspose.pdf.annotations/redactionannotation/
---
## RedactionAnnotation class


Представляет аннотацию Redact.

```cpp
class RedactionAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Принимает объект‑посетитель для обработки аннотации. |
| [Flatten](./flatten/)() override | Преобразует аннотацию в плоскую форму, т.е. удаляет аннотацию и добавляет её. |
| [get_AnnotationType](./get_annotationtype/)() override | Получает тип аннотации. |
| [get_BorderColor](./get_bordercolor/)() | Получает цвет границы, который отображается, когда редактирование не активно. |
| [get_DefaultAppearance](./get_defaultappearance/)() | Получает строку внешнего вида по умолчанию, используемую при форматировании текста. |
| [get_FillColor](./get_fillcolor/)() | Получает цвет для заполнения аннотации. |
| [get_FontSize](./get_fontsize/)() const | Получает размер шрифта для OverlayText. |
| [get_OverlayText](./get_overlaytext/)() | Получает текст для печати на аннотации redact. |
| [get_QuadPoint](./get_quadpoint/)() | Массив чисел размером 8xN, определяющий координаты области содержимого, которую предполагается удалить. |
| [get_Repeat](./get_repeat/)() | Если true, наложенный текст будет повторяться на аннотации. |
| [get_TextAlignment](./get_textalignment/)() | Получает. Выравнивание наложения [Text](../../aspose.pdf.text/). |
| [Redact](./redact/)() | Сводит аннотацию к плоскому виду и редактирует содержимое страницы (т. е. удаляет текст и изображение под отредактированной аннотацией) |
| [RedactionAnnotation](./redactionannotation/)(const System::SharedPtr\<Document\>\&) | Конструктор для [RedactionAnnotation](./). Для использования в Generator. |
| [RedactionAnnotation](./redactionannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Конструктор для RedactAnnotation. |
| [set_BorderColor](./set_bordercolor/)(const System::SharedPtr\<Aspose::Pdf::Color\>\&) | Устанавливает цвет границы, которая рисуется, когда редактирование не активно. |
| [set_DefaultAppearance](./set_defaultappearance/)(const System::String\&) | Устанавливает строку отображения по умолчанию, используемую при форматировании текста. |
| [set_FillColor](./set_fillcolor/)(const System::SharedPtr\<Aspose::Pdf::Color\>\&) | Устанавливает цвет для заполнения аннотации. |
| [set_FontSize](./set_fontsize/)(float) | Устанавливает размер шрифта для OverlayText. |
| [set_OverlayText](./set_overlaytext/)(const System::String\&) | Устанавливает текст для печати на редактируемой аннотации. |
| [set_QuadPoint](./set_quadpoint/)(const System::ArrayPtr\<System::SharedPtr\<Point\>\>\&) | Массив чисел размером 8xN, определяющий координаты области содержимого, которую предполагается удалить. |
| [set_Repeat](./set_repeat/)(bool) | Если true, наложенный текст будет повторяться на аннотации. |
| [set_TextAlignment](./set_textalignment/)(Aspose::Pdf::HorizontalAlignment) | Устанавливает. Выравнивание наложения [Text](../../aspose.pdf.text/). |
## См. также

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
