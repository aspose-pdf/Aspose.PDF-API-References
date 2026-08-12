---
title: "Aspose::Pdf::Annotations::LineAnnotation класс"
linktitle: "LineAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::LineAnnotation класс. Класс, представляющий аннотацию линии в C++."
type: docs
weight: 5700
url: /ru/cpp/aspose.pdf.annotations/lineannotation/
---
## LineAnnotation class


Класс, представляющий аннотацию линии.

```cpp
class LineAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Принимает посетителя для обработки аннотации. |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Обновляет начальные и конечные точки в соответствии с преобразованием матрицы. |
| [get_AnnotationType](./get_annotationtype/)() override | Получает тип аннотации. |
| [get_CaptionOffset](./get_captionoffset/)() | Получает смещение текста подписи от его обычного положения. |
| [get_CaptionPosition](./get_captionposition/)() | Получает позицию подписи аннотации. |
| [get_Ending](./get_ending/)() | Получает конечную точку линии. |
| [get_EndingStyle](./get_endingstyle/)() | Получает стиль окончания для конечной точки линии. |
| [get_Intent](./get_intent/)() | Получает назначение аннотации линии. |
| [get_InteriorColor](./get_interiorcolor/)() | Получает внутренний цвет аннотации. |
| [get_LeaderLine](./get_leaderline/)() | Получает длину направляющей линии. |
| [get_LeaderLineExtension](./get_leaderlineextension/)() | Получает длину расширения направляющей линии. |
| [get_LeaderLineOffset](./get_leaderlineoffset/)() | Получает смещение направляющей линии. |
| [get_Measure](./get_measure/)() | единицы [Measure](../measure/) указаны для этой аннотации. |
| [get_ShowCaption](./get_showcaption/)() | Получает логический флаг, определяющий, должно ли содержимое отображаться как подпись. |
| [get_Starting](./get_starting/)() | Получает начальную точку линии. |
| [get_StartingStyle](./get_startingstyle/)() | Получает стиль окончания линии для начальной точки. |
| [LineAnnotation](./lineannotation/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Point\>\&, const System::SharedPtr\<Point\>\&) | Конструктор для использования с Generator. |
| [LineAnnotation](./lineannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::SharedPtr\<Point\>\&, const System::SharedPtr\<Point\>\&) | Создает новую аннотацию Line на указанной странице. |
| [set_CaptionOffset](./set_captionoffset/)(const System::SharedPtr\<Point\>\&) | Устанавливает смещение текста подписи от его обычного положения. |
| [set_CaptionPosition](./set_captionposition/)(Aspose::Pdf::Annotations::CaptionPosition) | Устанавливает позицию подписи аннотации. |
| [set_Ending](./set_ending/)(const System::SharedPtr\<Point\>\&) | Устанавливает конечную точку линии. |
| [set_EndingStyle](./set_endingstyle/)(LineEnding) | Устанавливает стиль окончания для конечной точки линии. |
| [set_Intent](./set_intent/)(LineIntent) | Устанавливает назначение аннотации линии. |
| [set_InteriorColor](./set_interiorcolor/)(const System::SharedPtr\<Aspose::Pdf::Color\>\&) | Устанавливает внутренний цвет аннотации. |
| [set_LeaderLine](./set_leaderline/)(double) | Устанавливает длину направляющей линии. |
| [set_LeaderLineExtension](./set_leaderlineextension/)(double) | Устанавливает длину расширения направляющей линии. |
| [set_LeaderLineOffset](./set_leaderlineoffset/)(double) | Устанавливает смещение направляющей линии. |
| [set_Measure](./set_measure/)(const System::SharedPtr\<Aspose::Pdf::Annotations::Measure\>\&) | единицы [Measure](../measure/) указаны для этой аннотации. |
| [set_ShowCaption](./set_showcaption/)(bool) | Устанавливает логический флаг, определяющий, должно ли содержимое отображаться в виде подписи. |
| [set_Starting](./set_starting/)(const System::SharedPtr\<Point\>\&) | Устанавливает начальную точку линии. |
| [set_StartingStyle](./set_startingstyle/)(LineEnding) | Устанавливает стиль окончания линии для начальной точки линии. |
## См. также

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
