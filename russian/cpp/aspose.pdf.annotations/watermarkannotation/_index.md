---
title: "Aspose::Pdf::Annotations::WatermarkAnnotation class"
linktitle: "WatermarkAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::WatermarkAnnotation class. Класс описывает объект аннотации Watermark в C++."
type: docs
weight: 11700
url: /ru/cpp/aspose.pdf.annotations/watermarkannotation/
---
## WatermarkAnnotation class


Класс описывает объект аннотации [Watermark](../../aspose.pdf/watermark/).

```cpp
class WatermarkAnnotation : public Aspose::Pdf::Annotations::Annotation
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Применить посетитель к аннотации. |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Переопределяет определение в базовом классе пустым телом. |
| [get_AnnotationType](./get_annotationtype/)() override | Получает тип аннотации. |
| [get_FixedPrint](./get_fixedprint/)() | Объект фиксированной печати аннотации [Watermark](../../aspose.pdf/watermark/). |
| [get_Opacity](./get_opacity/)() const | Получает непрозрачность аннотации. |
| [set_Opacity](./set_opacity/)(double) | Устанавливает непрозрачность аннотации. |
| [SetText](./settext/)(const System::SharedPtr\<Facades::FormattedText\>\&) | Установить текст аннотации. |
| [SetTextAndState](./settextandstate/)(const System::ArrayPtr\<System::String\>\&, const System::SharedPtr\<Text::TextState\>\&) | Установить текст аннотации. |
| [WatermarkAnnotation](./watermarkannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Конструктор класса аннотации [Watermark](../../aspose.pdf/watermark/). |
## См. также

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
