---
title: "Метод Aspose::Pdf::Vector::SvgExtractionOptions::set_MinStrokeWidth"
linktitle: "set_MinStrokeWidth"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Vector::SvgExtractionOptions::set_MinStrokeWidth. Устанавливает минимальную ширину штриха, которая будет использоваться в результирующем SVG. Если в PDF используется более тонкий штрих, он будет заменён этой шириной. Значение по умолчанию — 0,5 в C++."
type: docs
weight: 1400
url: /ru/cpp/aspose.pdf.vector/svgextractionoptions/set_minstrokewidth/
---
## SvgExtractionOptions::set_MinStrokeWidth method


Устанавливает минимальную ширину штриха, которая будет использоваться в результирующем SVG. Если PDF использует более тонкую ширину штриха, она будет заменена на эту ширину. Значение по умолчанию — 0,5.

```cpp
void Aspose::Pdf::Vector::SvgExtractionOptions::set_MinStrokeWidth(double value)
```

## Примечания


Значение выражается в преобразованных единицах пользовательского пространства конвертируемой страницы PDF. По умолчанию 1 единица пользовательского пространства равна 1/72 дюйма (0,35 мм), но это может быть переопределено документом PDF. Преобразования могут влиять на фактическую минимальную ширину в генерируемом SVG.
## См. также

* Class [SvgExtractionOptions](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
