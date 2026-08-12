---
title: "Класс Aspose::Pdf::Vector::SvgExtractor"
linktitle: "SvgExtractor"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Vector::SvgExtractor. Представляет класс для извлечения SVG‑изображений со страницы в C++."
type: docs
weight: 800
url: /ru/cpp/aspose.pdf.vector/svgextractor/
---
## SvgExtractor class


Представляет класс для извлечения SVG‑изображений со страницы.

```cpp
class SvgExtractor : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Extract](./extract/)(const System::SharedPtr\<GraphicsAbsorber\>\&, System::Predicate\<System::SharedPtr\<GraphicElement\>\>, const System::SharedPtr\<Page\>\&) | Извлекает SVG‑изображение в строку из графических элементов, представленных [absorber](../) с фильтром‑предикатом. |
| [Extract](./extract/)(const System::SharedPtr\<GraphicsAbsorber\>\&, System::Predicate\<System::SharedPtr\<GraphicElement\>\>, const System::SharedPtr\<Page\>\&, const System::String\&) | Извлекает SVG‑изображение в файл из графических элементов, представленных [absorber](../) с фильтром‑предикатом. |
| [Extract](./extract/)(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\>\&, const System::SharedPtr\<Page\>\&) | Извлекает графические элементы в строку SVG. Параметры игнорируются — группировка, извлечение из прямоугольника. |
| [Extract](./extract/)(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\>\&, const System::SharedPtr\<Page\>\&, const System::String\&) | Извлекает графические элементы в единый файл SVG. Параметры игнорируются — группировка, извлечение из прямоугольника. |
| [Extract](./extract/)(const System::SharedPtr\<Page\>\&) | Извлекает SVG‑изображения со страницы в строки. |
| [Extract](./extract/)(const System::SharedPtr\<Page\>\&, const System::String\&) | Извлекает SVG‑изображения со страницы в файлы. |
| [SvgExtractor](./svgextractor/)() | Представляет класс для извлечения SVG‑изображений со страницы. |
| [SvgExtractor](./svgextractor/)(const System::SharedPtr\<SvgExtractionOptions\>\&) | Представляет класс для извлечения SVG‑изображений со страницы. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
