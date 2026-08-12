---
title: "Aspose::Pdf::Text::SystemFontsSubstitution class"
linktitle: "SystemFontsSubstitution"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::SystemFontsSubstitution class. Представляет класс стратегии замены шрифтов, который заменяет шрифты системными шрифтами в C++."
type: docs
weight: 3200
url: /ru/cpp/aspose.pdf.text/systemfontssubstitution/
---
## SystemFontsSubstitution class


Представляет класс стратегии замены шрифтов, заменяющей шрифты на системные.

```cpp
class SystemFontsSubstitution : public Aspose::Pdf::Text::FontSubstitution
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_DefaultFont](./get_defaultfont/)() | Получает шрифт замены по умолчанию. Шрифт используется, когда не найдено других подходящих замен, но исходный шрифт относится к целевой категории замены ([FontCategories](../)). |
| [get_FontCategories](./get_fontcategories/)() const | Получает категории шрифтов замены, которые должны быть заменены системными шрифтами. |
| [set_DefaultFont](./set_defaultfont/)(const System::SharedPtr\<Font\>\&) | Устанавливает шрифт замены по умолчанию. Шрифт используется, когда не найдено других подходящих замен, но исходный шрифт относится к целевой категории замены ([FontCategories](../)). |
| [set_FontCategories](./set_fontcategories/)(SubstitutionFontCategories) | Устанавливает категории шрифтов замены, которые должны быть заменены системными шрифтами. |
| [SystemFontsSubstitution](./systemfontssubstitution/)(SubstitutionFontCategories) | Инициализирует новый экземпляр класса [SystemFontsSubstitution](./). |
## См. также

* Class [FontSubstitution](../fontsubstitution/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
