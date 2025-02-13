---
title: Enum TextEditOptions.NoCharacterAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextEditOptionsNoCharacterAction enum. Action to perform if font does not contain required character
type: docs
weight: 9810
url: /net/aspose.pdf.text/texteditoptions.nocharacteraction/
---
## TextEditOptions.NoCharacterAction enumeration

Action to perform if font does not contain required character

```csharp
public enum NoCharacterAction
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| ThrowException | `0` | Throw exception |
| UseStandardFont | `1` | Repalce font to standard font which contains required character |
| ReplaceAnyway | `2` | Replace text anyway without font substitution |
| ReplaceFonts | `3` | Replaces fonts as necessary to ensure all characters in the text can be displayed. The font substitution algorithm follows these steps: 1. If the user explicitly sets the Font property, check if the specified font can display the desired characters. 2. If no user-defined font is set, search through fonts added via the [`Sources`](../fontrepository/sources/). 3. Analyze the text to identify its alphabet or script and suggest font names accordingly. Attempt to locate and use these fonts from the system. 4. As a fallback, search the system for any font capable of displaying the required characters. |
| UseCustomReplacementFont | `4` | Repalce font to defined replacement font |

### See Also

* class [TextEditOptions](../texteditoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


