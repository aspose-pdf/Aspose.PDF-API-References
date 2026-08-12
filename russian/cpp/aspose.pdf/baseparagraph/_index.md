---
title: "Класс Aspose::Pdf::BaseParagraph"
linktitle: "BaseParagraph"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::BaseParagraph. Представляет абстрактный базовый объект, который можно добавить на страницу (doc.Paragraphs.Add()) в C++."
type: docs
weight: 1000
url: /ru/cpp/aspose.pdf/baseparagraph/
---
## BaseParagraph class


Представляет абстрактный базовый объект, который можно добавить на страницу (doc.Paragraphs.Add()).

```cpp
class BaseParagraph : public System::ICloneable
```

## Методы

| Метод | Описание |
| --- | --- |
| [BaseParagraph](./baseparagraph/)() |  |
| [Clone](./clone/)() override | Клонирует этот экземпляр. Виртуальный метод. Всегда возвращает null. |
| virtual [get_HorizontalAlignment](./get_horizontalalignment/)() | Получает горизонтальное выравнивание абзаца. |
| virtual [get_Hyperlink](./get_hyperlink/)() | Получает гиперссылку фрагмента (для генератора PDF). |
| [get_IsFirstParagraphInColumn](./get_isfirstparagraphincolumn/)() const | Возвращает логическое значение, указывающее, будет ли этот абзац в следующей колонке. По умолчанию false. (для генерации PDF) |
| [get_IsInLineParagraph](./get_isinlineparagraph/)() const | Возвращает, является ли абзац встроенным. По умолчанию false. (для генерации PDF) |
| [get_IsInNewPage](./get_isinnewpage/)() const | Возвращает логическое значение, заставляющее этот абзац генерироваться на новой странице. По умолчанию false. (для генерации PDF) |
| [get_IsKeptWithNext](./get_iskeptwithnext/)() const | Возвращает логическое значение, указывающее, останется ли текущий абзац на той же странице вместе со следующим абзацем. По умолчанию false. (для генерации PDF) |
| [get_Margin](./get_margin/)() | Получает внешний отступ для абзаца (для генерации PDF) |
| virtual [get_VerticalAlignment](./get_verticalalignment/)() | Получает вертикальное выравнивание абзаца. |
| [get_ZIndex](./get_zindex/)() const | Возвращает целочисленное значение, указывающее порядок Z графика. График с большим ZIndex будет размещён поверх графика с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет находиться за текстом на странице. |
| virtual [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Устанавливает горизонтальное выравнивание абзаца. |
| virtual [set_Hyperlink](./set_hyperlink/)(System::SharedPtr\<Aspose::Pdf::Hyperlink\>) | Устанавливает гиперссылку фрагмента (для генератора PDF). |
| [set_IsFirstParagraphInColumn](./set_isfirstparagraphincolumn/)(bool) | Устанавливает логическое значение, указывающее, будет ли этот абзац в следующей колонке. По умолчанию false. (для генерации PDF) |
| [set_IsInLineParagraph](./set_isinlineparagraph/)(bool) | Устанавливает, что абзац является встроенным. По умолчанию false. (для генерации PDF) |
| [set_IsInNewPage](./set_isinnewpage/)(bool) | Устанавливает логическое значение, принуждающее этот абзац генерироваться на новой странице. По умолчанию false. (для генерации PDF) |
| [set_IsKeptWithNext](./set_iskeptwithnext/)(bool) | Устанавливает логическое значение, указывающее, остаётся ли текущий абзац на той же странице вместе со следующим абзацем. По умолчанию false. (для генерации PDF) |
| [set_Margin](./set_margin/)(const System::SharedPtr\<MarginInfo\>\&) | Устанавливает внешний отступ для абзаца (для генерации PDF) |
| virtual [set_VerticalAlignment](./set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Устанавливает вертикальное выравнивание абзаца. |
| [set_ZIndex](./set_zindex/)(int32_t) | Устанавливает целочисленное значение, указывающее порядок Z графика. График с большим ZIndex будет размещён поверх графика с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещён за текстом на странице. |
## См. также

* Class [ICloneable](../../system/icloneable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
