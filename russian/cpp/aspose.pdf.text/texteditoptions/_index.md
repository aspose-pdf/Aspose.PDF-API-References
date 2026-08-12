---
title: "класс Aspose::Pdf::Text::TextEditOptions"
linktitle: "TextEditOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "класс Aspose::Pdf::Text::TextEditOptions. Описывает параметры операций редактирования текста в C++."
type: docs
weight: 3800
url: /ru/cpp/aspose.pdf.text/texteditoptions/
---
## TextEditOptions class


Описывает параметры операций редактирования текста.

```cpp
class TextEditOptions : public Aspose::Pdf::Text::TextOptions
```

## Enums

| Перечисление | Описание |
| --- | --- |
| [ClippingPathsProcessingMode](./clippingpathsprocessingmode/) | Режимы обработки обрезающих путей. |
| [FontReplace](./fontreplace/) | Поведение замены [Font](../font/). |
| [LanguageTransformation](./languagetransformation/) | Режимы трансформации языка. |
| [NoCharacterAction](./nocharacteraction/) | Действие, которое следует выполнить, если шрифт не содержит требуемый символ. |
## Методы

| Метод | Описание |
| --- | --- |
| [get_AllowLanguageTransformation](./get_allowlanguagetransformation/)() const | Получает значение, позволяющее использовать трансформацию языка при добавлении или редактировании текста. true — трансформация языка будет применена при необходимости (значение по умолчанию). false — трансформация языка НЕ будет применена. |
| [get_ClippingPathsProcessing](./get_clippingpathsprocessing/)() const | Получает режим обработки обрезающего пути отредактированного текста. |
| [get_FontReplaceBehavior](./get_fontreplacebehavior/)() const | Получает режим, определяющий поведение в сценариях замены шрифтов. |
| [get_LanguageTransformationBehavior](./get_languagetransformationbehavior/)() const | Получает режим, определяющий поведение в сценариях трансформации языка. |
| [get_NoCharacterBehavior](./get_nocharacterbehavior/)() const | Получает режим, определяющий поведение в случае, если шрифты не содержат требуемые символы. |
| [get_ReplacementFont](./get_replacementfont/)() const | Получает шрифт, используемый для замены, если пользовательский шрифт не содержит требуемый символ. |
| [get_ToAttemptGetUnderlineFromSource](./get_toattemptgetunderlinefromsource/)() const | Получает значение, позволяющее искать подчеркивание текста на странице исходного документа. (Устарело) Пожалуйста, используйте вместо этого TextSearchOptions.SearchForTextRelatedGraphics. |
| [set_AllowLanguageTransformation](./set_allowlanguagetransformation/)(bool) | Устанавливает значение, позволяющее использовать трансформацию языка при добавлении или редактировании текста. true — трансформация языка будет применена при необходимости (значение по умолчанию). false — трансформация языка НЕ будет применена. |
| [set_ClippingPathsProcessing](./set_clippingpathsprocessing/)(TextEditOptions::ClippingPathsProcessingMode) | Получает режим обработки обрезающего пути отредактированного текста. |
| [set_FontReplaceBehavior](./set_fontreplacebehavior/)(TextEditOptions::FontReplace) | Получает режим, определяющий поведение в сценариях замены шрифтов. |
| [set_LanguageTransformationBehavior](./set_languagetransformationbehavior/)(TextEditOptions::LanguageTransformation) | Получает режим, определяющий поведение в сценариях трансформации языка. |
| [set_NoCharacterBehavior](./set_nocharacterbehavior/)(TextEditOptions::NoCharacterAction) | Устанавливает режим, определяющий поведение в случае, если шрифты не содержат запрашиваемые символы. |
| [set_ReplacementFont](./set_replacementfont/)(const System::SharedPtr\<Font\>\&) | Устанавливает шрифт, используемый для замены, если пользовательский шрифт не содержит требуемый символ. |
| [set_ToAttemptGetUnderlineFromSource](./set_toattemptgetunderlinefromsource/)(bool) | Устанавливает значение, позволяющее искать подчеркивание текста на странице исходного документа. (Устарело) Пожалуйста, используйте TextSearchOptions.SearchForTextRelatedGraphics вместо этого. |
| [TextEditOptions](./texteditoptions/)(TextEditOptions::NoCharacterAction) | Инициализирует новый экземпляр объекта [TextEditOptions](./) для указанного режима поведения без символов. |
| [TextEditOptions](./texteditoptions/)(TextEditOptions::FontReplace) | Инициализирует новый экземпляр объекта [TextEditOptions](./) для указанного режима поведения замены шрифта. |
| [TextEditOptions](./texteditoptions/)(bool) | Инициализирует новый экземпляр объекта [TextEditOptions](./) для указанного разрешения преобразования языка. |
| [TextEditOptions](./texteditoptions/)(TextEditOptions::LanguageTransformation) | Инициализирует новый экземпляр объекта [TextEditOptions](./) для указанного режима поведения преобразования языка. |
## См. также

* Class [TextOptions](../textoptions/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
