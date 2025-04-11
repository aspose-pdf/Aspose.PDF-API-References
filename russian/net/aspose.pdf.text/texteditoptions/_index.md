---
title: Class TextEditOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Text.TextEditOptions. Описывает параметры операций редактирования текста
type: docs
weight: 10820
url: /ru/net/aspose.pdf.text/texteditoptions/
---
## Класс TextEditOptions

Описывает параметры операций редактирования текста.

```csharp
public sealed class TextEditOptions : TextOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextEditOptions](texteditoptions/#constructor)(bool) | Инициализирует новый экземпляр объекта `TextEditOptions` для указанного разрешения на преобразование языка. |
| [TextEditOptions](texteditoptions/#constructor_1)(FontReplace) | Инициализирует новый экземпляр объекта `TextEditOptions` для указанного режима поведения замены шрифта. |
| [TextEditOptions](texteditoptions/#constructor_2)(LanguageTransformation) | Инициализирует новый экземпляр объекта `TextEditOptions` для указанного режима поведения преобразования языка. |
| [TextEditOptions](texteditoptions/#constructor_3)(NoCharacterAction) | Инициализирует новый экземпляр объекта `TextEditOptions` для указанного режима поведения без символов. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AllowLanguageTransformation](../../aspose.pdf.text/texteditoptions/allowlanguagetransformation/) { get; set; } | Получает или задает значение, которое разрешает использование преобразования языка при добавлении или редактировании текста. true - преобразование языка будет применено, если это необходимо (значение по умолчанию). false - преобразование языка НЕ будет применено. |
| [ClippingPathsProcessing](../../aspose.pdf.text/texteditoptions/clippingpathsprocessing/) { get; set; } | Получает режим обработки обрезанных путей редактируемого текста. |
| [FontReplaceBehavior](../../aspose.pdf.text/texteditoptions/fontreplacebehavior/) { get; set; } | Получает режим, который определяет поведение для сценариев замены шрифтов. |
| [LanguageTransformationBehavior](../../aspose.pdf.text/texteditoptions/languagetransformationbehavior/) { get; set; } | Получает режим, который определяет поведение для сценариев преобразования языка. |
| [NoCharacterBehavior](../../aspose.pdf.text/texteditoptions/nocharacterbehavior/) { get; set; } | Получает или задает режим, который определяет поведение в случае, если шрифты не содержат запрашиваемых символов. |
| [ReplacementFont](../../aspose.pdf.text/texteditoptions/replacementfont/) { get; set; } | Получает или задает шрифт, используемый для замены, если пользовательский шрифт не содержит необходимый символ |
| [ToAttemptGetUnderlineFromSource](../../aspose.pdf.text/texteditoptions/toattemptgetunderlinefromsource/) { get; set; } | Получает или задает значение, которое разрешает поиск подчеркивания текста на странице исходного документа. (Устарело) Пожалуйста, используйте TextSearchOptions.SearchForTextRelatedGraphics вместо этого. |

### См. также

* класс [TextOptions](../textoptions/)
* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../)