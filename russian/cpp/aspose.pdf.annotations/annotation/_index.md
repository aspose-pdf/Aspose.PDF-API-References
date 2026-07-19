---
title: "Aspose::Pdf::Annotations::Annotation class"
linktitle: "Annotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::Annotation class. Класс, представляющий объект аннотации в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf.annotations/annotation/
---
## Annotation class


Класс, представляющий объект аннотации.

```cpp
class Annotation : public Aspose::Pdf::BaseParagraph
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) | Принимает посетитель для обработки аннотации. |
| virtual [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) | Обновляет параметры и внешний вид в соответствии с матричным преобразованием. |
| virtual [Flatten](./flatten/)() | Размещает содержимое аннотации непосредственно на странице, объект аннотации будет удалён. |
| [get_Actions](./get_actions/)() | Получает список действий аннотации. |
| virtual [get_ActiveState](./get_activestate/)() | Получает текущее состояние внешнего вида аннотации. |
| [get_Alignment](./get_alignment/)() | [Аннотация](./) выравнивание. Это свойство устарело. Используйте HorizontalAligment вместо него. |
| virtual [get_AnnotationType](./get_annotationtype/)() | Получает тип аннотации. |
| [get_Appearance](./get_appearance/)() | Получает словарь внешнего вида аннотации. |
| [get_Border](./get_border/)() const | Получает характеристики границы аннотации. [Граница](../border/) |
| [get_Characteristics](./get_characteristics/)() | Получает характеристики аннотации. |
| [get_Color](./get_color/)() | Получает цвет аннотации. |
| [get_Contents](./get_contents/)() | Получает текст аннотации. |
| [get_Flags](./get_flags/)() | Флаги аннотации. |
| [get_FullName](./get_fullname/)() | Получает полностью квалифицированное имя аннотации. |
| virtual [get_Height](./get_height/)() | Получает высоту аннотации. |
| [get_HorizontalAlignment](./get_horizontalalignment/)() override | Получает выравнивание текста для аннотации. |
| [get_Modified](./get_modified/)() | Получает дату и время последнего изменения аннотации. |
| [get_Name](./get_name/)() | Получает имя аннотации на странице. |
| virtual [get_PageIndex](./get_pageindex/)() | Получает индекс страницы, содержащей аннотацию. |
| virtual [get_Rect](./get_rect/)() | Получает прямоугольник аннотации. |
| [get_States](./get_states/)() | Получает словарь внешнего вида аннотации. |
| [get_TextHorizontalAlignment](./get_texthorizontalalignment/)() | Получает выравнивание текста для аннотации. |
| static [get_UpdateAppearanceOnConvert](./get_updateappearanceonconvert/)() | Если true, внешний вид аннотации будет обновлён перед преобразованием PF‑документа в изображение. Это позволяет корректно преобразовать поля, но, вероятно, требует больше времени. |
| static [get_UseFontSubset](./get_usefontsubset/)() | Если это свойство установлено в true, шрифты будут добавлены в документ как подмножества. Значение по умолчанию — true. |
| virtual [get_Width](./get_width/)() | Получает ширину аннотации. |
| [GetRectangle](./getrectangle/)(bool) | Возвращает прямоугольник аннотации с учётом поворота страницы. |
| virtual [set_ActiveState](./set_activestate/)(System::String) | Устанавливает текущее состояние внешнего вида аннотации. |
| [set_Alignment](./set_alignment/)(TextAlignment) | [Аннотация](./) выравнивание. Это свойство устарело. Используйте HorizontalAligment вместо него. |
| [set_Border](./set_border/)(const System::SharedPtr\<Aspose::Pdf::Annotations::Border\>\&) | Устанавливает характеристики границы аннотации. [Граница](../border/) |
| [set_Color](./set_color/)(const System::SharedPtr\<Aspose::Pdf::Color\>\&) | Устанавливает цвет аннотации. |
| [set_Contents](./set_contents/)(const System::String\&) | Устанавливает текст аннотации. |
| [set_Flags](./set_flags/)(AnnotationFlags) | Флаги аннотации. |
| virtual [set_Height](./set_height/)(double) | Устанавливает высоту аннотации. |
| [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) override | Устанавливает выравнивание текста для аннотации. |
| [set_Modified](./set_modified/)(System::DateTime) | Устанавливает дату и время последнего изменения аннотации. |
| [set_Name](./set_name/)(const System::String\&) | Устанавливает имя аннотации на странице. |
| virtual [set_Rect](./set_rect/)(System::SharedPtr\<Rectangle\>) | Устанавливает прямоугольник аннотации. |
| [set_TextHorizontalAlignment](./set_texthorizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Устанавливает выравнивание текста для аннотации. |
| static [set_UpdateAppearanceOnConvert](./set_updateappearanceonconvert/)(bool) | Если true, внешний вид аннотации будет обновлён перед преобразованием PF‑документа в изображение. Это позволяет корректно преобразовать поля, но, вероятно, требует больше времени. |
| static [set_UseFontSubset](./set_usefontsubset/)(bool) | Если это свойство установлено в true, шрифты будут добавлены в документ как подмножества. Значение по умолчанию — true. |
| virtual [set_Width](./set_width/)(double) | Устанавливает ширину аннотации. |
## См. также

* Class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
