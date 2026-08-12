---
title: "Aspose::Pdf::Annotations::FreeTextAnnotation class"
linktitle: "FreeTextAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::FreeTextAnnotation class. Представляет свободную текстовую аннотацию, которая отображает текст непосредственно на странице. В отличие от обычной текстовой аннотации, свободная текстовая аннотация не имеет состояния открыто/закрыто; вместо отображения во всплывающем окне текст всегда виден в C++."
type: docs
weight: 4000
url: /ru/cpp/aspose.pdf.annotations/freetextannotation/
---
## FreeTextAnnotation class


Представляет аннотацию свободного текста, отображающую текст непосредственно на странице. В отличие от обычной текстовой аннотации, аннотация свободного текста не имеет состояний открыто/закрыто; вместо отображения во всплывающем окне текст всегда виден.

```cpp
class FreeTextAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Принимает объект‑посетитель для обработки аннотации. |
| [FreeTextAnnotation](./freetextannotation/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Aspose::Pdf::Annotations::DefaultAppearance\>\&) | Конструктор для использования с Generator. |
| [FreeTextAnnotation](./freetextannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::SharedPtr\<Aspose::Pdf::Annotations::DefaultAppearance\>\&) | Создаёт новую аннотацию FreeText на указанной странице. |
| [get_AnnotationType](./get_annotationtype/)() override | Получает тип аннотации. |
| [get_Callout](./get_callout/)() | Массив точек, задающих линию выноски. |
| [get_DefaultAppearance](./get_defaultappearance/)() | Получает строку внешнего вида по умолчанию, используемую при форматировании текста. |
| [get_DefaultAppearanceObject](./get_defaultappearanceobject/)() | Объект, представляющий внешний вид по умолчанию аннотации FreeText. |
| [get_DefaultStyle](./get_defaultstyle/)() | Получает строку стиля по умолчанию. |
| [get_EndingStyle](./get_endingstyle/)() | Получает стиль окончания линии для конечной точки линии. |
| [get_Intent](./get_intent/)() | Получает назначение свободной текстовой аннотации. |
| [get_Justification](./get_justification/)() | Получает или задаёт код, определяющий форму выравнивания (justification) текста аннотации. |
| [get_Rotate](./get_rotate/)() | Угол вращения аннотации. |
| [get_StartingStyle](./get_startingstyle/)() | Получает стиль окончания линии для конечной точки линии. OThis property устарела, пожалуйста, используйте EndingStyle. |
| [get_TextRectangle](./get_textrectangle/)() | [Rectangle](../../aspose.pdf/rectangle/) описывающий численные различия между двумя прямоугольниками: запись Rect аннотации и прямоугольник, содержащийся внутри этого прямоугольника. Внутренний прямоугольник — это место, где должен отображаться текст аннотации. |
| [get_TextStyle](./get_textstyle/)() | Получает стиль текста в отображении. Когда стиль текста изменяется, отображение текста обновляется. |
| [set_Callout](./set_callout/)(const System::ArrayPtr\<System::SharedPtr\<Point\>\>\&) | Массив точек, задающих линию выноски. |
| [set_DefaultAppearance](./set_defaultappearance/)(const System::String\&) | Устанавливает строку отображения по умолчанию, используемую при форматировании текста. |
| [set_DefaultStyle](./set_defaultstyle/)(const System::String\&) | Устанавливает строку стиля по умолчанию. |
| [set_EndingStyle](./set_endingstyle/)(LineEnding) | Устанавливает стиль окончания линии для конечной точки линии. |
| [set_Intent](./set_intent/)(FreeTextIntent) | Устанавливает назначение свободной текстовой аннотации. |
| [set_Justification](./set_justification/)(Aspose::Pdf::Annotations::Justification) | Получает или задаёт код, определяющий форму выравнивания (justification) текста аннотации. |
| [set_Rotate](./set_rotate/)(Rotation) | Угол вращения аннотации. |
| [set_StartingStyle](./set_startingstyle/)(LineEnding) | Устанавливает стиль окончания линии для конечной точки линии. Это свойство устарело, пожалуйста, используйте EndingStyle. |
| [set_TextRectangle](./set_textrectangle/)(const System::SharedPtr\<Rectangle\>\&) | [Rectangle](../../aspose.pdf/rectangle/) описывающий численные различия между двумя прямоугольниками: запись Rect аннотации и прямоугольник, содержащийся внутри этого прямоугольника. Внутренний прямоугольник — это место, где должен отображаться текст аннотации. |
| [set_TextStyle](./set_textstyle/)(const System::SharedPtr\<Aspose::Pdf::Annotations::TextStyle\>\&) | Устанавливает стиль текста в отображении. Когда стиль текста изменяется, отображение текста обновляется. |
| [SetTextStyle](./settextstyle/)(RichTextFontStyles, const System::String\&, double, System::Drawing::Color) | Устанавливает форматирование, определяемое параметром textStyle, для всего текста аннотации. |
| [SetTextStyle](./settextstyle/)(int32_t, int32_t, RichTextFontStyles) | Устанавливает форматирование, определяемое параметром textStyle, для фрагмента текста от индекса fromInd до индекса toInd. |
## См. также

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
