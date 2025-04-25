---
title: Class TextEditOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextEditOptions class. Descubes options of text edit operations
type: docs
weight: 10950
url: /net/aspose.pdf.text/texteditoptions/
---
## TextEditOptions class

Descubes options of text edit operations.

```csharp
public sealed class TextEditOptions : TextOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TextEditOptions](texteditoptions/#constructor)(bool) | Initializes new instance of the `TextEditOptions` object for the specified language transformation permission. |
| [TextEditOptions](texteditoptions/#constructor_1)(FontReplace) | Initializes new instance of the `TextEditOptions` object for the specified font replacement behavior mode. |
| [TextEditOptions](texteditoptions/#constructor_2)(LanguageTransformation) | Initializes new instance of the `TextEditOptions` object for the specified language transformation behavior mode. |
| [TextEditOptions](texteditoptions/#constructor_3)(NoCharacterAction) | Initializes new instance of the `TextEditOptions` object for the specified no-character behavior mode. |

## Properties

| Name | Description |
| --- | --- |
| [AllowLanguageTransformation](../../aspose.pdf.text/texteditoptions/allowlanguagetransformation/) { get; set; } | Gets or sets value that permits usage of language transformation during adding or editing of text. true - language transformation will be applied if necessary (default value). false - language transformation will NOT be applied. |
| [ClippingPathsProcessing](../../aspose.pdf.text/texteditoptions/clippingpathsprocessing/) { get; set; } | Gets mode for processing clipping path of the edited text. |
| [FontReplaceBehavior](../../aspose.pdf.text/texteditoptions/fontreplacebehavior/) { get; set; } | Gets mode that defines behavior for fonts replacement scenarios. |
| [LanguageTransformationBehavior](../../aspose.pdf.text/texteditoptions/languagetransformationbehavior/) { get; set; } | Gets mode that defines behavior for language transformation scenarios. |
| [NoCharacterBehavior](../../aspose.pdf.text/texteditoptions/nocharacterbehavior/) { get; set; } | Gets or sets mode that defines behavior in case fonts don't contain requested characters. |
| [ReplacementFont](../../aspose.pdf.text/texteditoptions/replacementfont/) { get; set; } | Gets or sets font used for replacing if user font does not contain required character |
| [ToAttemptGetUnderlineFromSource](../../aspose.pdf.text/texteditoptions/toattemptgetunderlinefromsource/) { get; set; } | Gets or sets value that permits searching for text underlining on the page of source document. (Obsolete) Please use TextSearchOptions.SearchForTextRelatedGraphics instead this. |

### See Also

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


