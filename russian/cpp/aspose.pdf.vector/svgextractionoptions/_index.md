---
title: "Aspose::Pdf::Vector::SvgExtractionOptions class"
linktitle: "SvgExtractionOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Vector::SvgExtractionOptions class. Представляет класс параметров для извлечения векторной графики со страницы PDF‑документа в C++."
type: docs
weight: 700
url: /ru/cpp/aspose.pdf.vector/svgextractionoptions/
---
## SvgExtractionOptions class


Представляет класс параметров для извлечения векторной графики со страницы PDF‑документа.

```cpp
class SvgExtractionOptions : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_AutoGrouping](./get_autogrouping/)() const | Получает и задает параметр автоматической группировки subpath‑ов в изображения. Этот параметр исключает параметр [GroupStrength](../). |
| [get_ExtractEverySubPathToSvg](./get_extracteverysubpathtosvg/)() const | Получает и задает параметр, позволяющий извлекать каждый subpath из PDF‑документа в отдельные SVG‑изображения. |
| [get_ExtractionAreaBound](./get_extractionareabound/)() const | Получает и задает ограничивающий прямоугольник, определяющий область извлечения для SVG‑извлечения. |
| [get_GroupStrength](./get_groupstrength/)() const | Получает и задает параметр Сила группировки subpath‑ов в изображения. Позволяет настроить степень группировки subpath‑ов. Диапазон значений от 0 до 1. Значение 0 соответствует включенному параметру [ExtractEverySubPathToSvg](../). Значение 1 создаст одно изображение для всех векторных путей на странице. Параметр оказывает влияние, когда [AutoGrouping](../) отключён. Значение по умолчанию — **0.8**. |
| [get_MinStrokeWidth](./get_minstrokewidth/)() const | Получает минимальную ширину штриха, которая будет использована в результирующем SVG. Если в PDF используется более тонкая ширина штриха, она будет заменена этой шириной. Значение по умолчанию — 0.5. |
| [get_StrictExtractionAreaBoundCheck](./get_strictextractionareaboundcheck/)() const | Получает и задает параметр, строго проверяющий, находятся ли subpath‑ы внутри указанного прямоугольника в [ExtractionAreaBound](../). Если параметр установлен в false, то subpath‑ы, не полностью включённые в [ExtractionAreaBound](../), будут извлечены. Значение по умолчанию — **True**. |
| [get_UnpackPageContentXForm](./get_unpackpagecontentxform/)() const | Получает и задает флаг, определяющий, следует ли распаковывать найденные на страницах XFrom. Элементы XFrom могут оказаться в разных SVG‑файлах. Распаковываются только XForms, отрисованные инструкциями Do из содержимого страницы. Вложенные XForms не распаковываются. |
| [get_UnpackXFormPredicate](./get_unpackxformpredicate/)() const | Получает и задает параметр, позволяющий распаковывать только [XForm](../../aspose.pdf/xform/), соответствующий указанному предикату. |
| [set_AutoGrouping](./set_autogrouping/)(bool) | Получает и задает параметр автоматической группировки subpath‑ов в изображения. Этот параметр исключает параметр [GroupStrength](../). |
| [set_ExtractEverySubPathToSvg](./set_extracteverysubpathtosvg/)(bool) | Получает и задает параметр, позволяющий извлекать каждый subpath из PDF‑документа в отдельные SVG‑изображения. |
| [set_ExtractionAreaBound](./set_extractionareabound/)(const System::SharedPtr\<Rectangle\>\&) | Получает и задает ограничивающий прямоугольник, определяющий область извлечения для SVG‑извлечения. |
| [set_GroupStrength](./set_groupstrength/)(double) | Получает и задает параметр Сила группировки subpath‑ов в изображения. Позволяет настроить степень группировки subpath‑ов. Диапазон значений от 0 до 1. Значение 0 соответствует включенному параметру [ExtractEverySubPathToSvg](../). Значение 1 создаст одно изображение для всех векторных путей на странице. Параметр оказывает влияние, когда [AutoGrouping](../) отключён. Значение по умолчанию — **0.8**. |
| [set_MinStrokeWidth](./set_minstrokewidth/)(double) | Устанавливает минимальную ширину штриха, которая будет использоваться в результирующем SVG. Если PDF использует более тонкую ширину штриха, она будет заменена на эту ширину. Значение по умолчанию — 0,5. |
| [set_StrictExtractionAreaBoundCheck](./set_strictextractionareaboundcheck/)(bool) | Получает и задает параметр, строго проверяющий, находятся ли subpath‑ы внутри указанного прямоугольника в [ExtractionAreaBound](../). Если параметр установлен в false, то subpath‑ы, не полностью включённые в [ExtractionAreaBound](../), будут извлечены. Значение по умолчанию — **True**. |
| [set_UnpackPageContentXForm](./set_unpackpagecontentxform/)(bool) | Получает и задает флаг, определяющий, следует ли распаковывать найденные на страницах XFrom. Элементы XFrom могут оказаться в разных SVG‑файлах. Распаковываются только XForms, отрисованные инструкциями Do из содержимого страницы. Вложенные XForms не распаковываются. |
| [set_UnpackXFormPredicate](./set_unpackxformpredicate/)(System::Predicate\<System::SharedPtr\<XFormPlacement\>\>) | Получает и задает параметр, позволяющий распаковывать только [XForm](../../aspose.pdf/xform/), соответствующий указанному предикату. |
| [SvgExtractionOptions](./svgextractionoptions/)() | Создаёт экземпляр класса [SvgExtractionOptions](./). |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
