---
title: "Класс TextEditOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Text.TextEditOptions. Описывает параметры операций редактирования текста"
type: docs
weight: 11000
url: /ru/net/aspose.pdf.text/texteditoptions/
---
## TextEditOptions class

Описывает параметры операций редактирования текста.

```csharp
public sealed class TextEditOptions : TextOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextEditOptions](texteditoptions/#constructor)(bool) | Инициализирует новый экземпляр объекта `TextEditOptions` для указанного разрешения трансформации языка. |
| [TextEditOptions](texteditoptions/#constructor_1)(FontReplace) | Инициализирует новый экземпляр объекта `TextEditOptions` для указанного режима поведения замены шрифтов. |
| [TextEditOptions](texteditoptions/#constructor_2)(LanguageTransformation) | Инициализирует новый экземпляр объекта `TextEditOptions` для указанного режима поведения трансформации языка. |
| [TextEditOptions](texteditoptions/#constructor_3)(NoCharacterAction) | Инициализирует новый экземпляр объекта `TextEditOptions` для указанного режима поведения при отсутствии символов. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AllowLanguageTransformation](../../aspose.pdf.text/texteditoptions/allowlanguagetransformation/) { get; set; } | Получает или задает значение, позволяющее использовать трансформацию языка при добавлении или редактировании текста. true — трансформация языка будет применена при необходимости (значение по умолчанию). false — трансформация языка НЕ будет применена. |
| [ClippingPathsProcessing](../../aspose.pdf.text/texteditoptions/clippingpathsprocessing/) { get; set; } | Получает режим обработки обрезающего пути отредактированного текста. |
| [FontReplaceBehavior](../../aspose.pdf.text/texteditoptions/fontreplacebehavior/) { get; set; } | Получает режим, определяющий поведение в сценариях замены шрифтов. |
| [LanguageTransformationBehavior](../../aspose.pdf.text/texteditoptions/languagetransformationbehavior/) { get; set; } | Получает режим, определяющий поведение в сценариях трансформации языка. |
| [NoCharacterBehavior](../../aspose.pdf.text/texteditoptions/nocharacterbehavior/) { get; set; } | Получает или задает режим, определяющий поведение в случае, если шрифты не содержат требуемые символы. |
| [ReplacementFont](../../aspose.pdf.text/texteditoptions/replacementfont/) { get; set; } | Получает или задает шрифт, используемый для замены, если пользовательский шрифт не содержит требуемый символ. |
| [ToAttemptGetUnderlineFromSource](../../aspose.pdf.text/texteditoptions/toattemptgetunderlinefromsource/) { get; set; } | Получает или задает значение, позволяющее искать подчеркивание текста на странице исходного документа. (Устарело) Пожалуйста, используйте TextSearchOptions.SearchForTextRelatedGraphics вместо этого. |

### См. также

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


