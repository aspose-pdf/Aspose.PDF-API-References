---
title: "Aspose::Pdf::Annotations::TextMarkupAnnotation класс"
linktitle: "TextMarkupAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::TextMarkupAnnotation класс. Абстрактный базовый класс для аннотаций разметки текста на C++."
type: docs
weight: 11300
url: /ru/cpp/aspose.pdf.annotations/textmarkupannotation/
---
## TextMarkupAnnotation class


Абстрактный базовый класс для текстовых разметочных аннотаций.

```cpp
class TextMarkupAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Методы

| Метод | Описание |
| --- | --- |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Обновляет QuadPoints в соответствии с преобразованием матрицы. |
| [get_QuadPoints](./get_quadpoints/)() | Получает массив точек, задающих координаты n четырёхугольников. Каждый четырёхугольник охватывает слово или группу смежных слов в тексте, лежащем в основе аннотации. |
| [GetMarkedText](./getmarkedtext/)() | Получает текст под разметкой аннотации в виде строки. |
| [GetMarkedTextFragments](./getmarkedtextfragments/)() | Получает текст под разметкой аннотации как [TextFragmentCollection](../). |
| [set_QuadPoints](./set_quadpoints/)(const System::ArrayPtr\<System::SharedPtr\<Point\>\>\&) | Устанавливает массив точек, задающих координаты n четырёхугольников. Каждый четырёхугольник охватывает слово или группу смежных слов в тексте, лежащем в основе аннотации. |
## См. также

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
