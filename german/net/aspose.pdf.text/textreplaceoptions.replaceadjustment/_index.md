---
title: Enum TextReplaceOptions.ReplaceAdjustment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextReplaceOptionsReplaceAdjustment Enum. Bestimmt die Aktion, die nach dem Ersetzen eines Textfragmentes durch einen kürzeren Text durchgeführt wird. None - keine Aktion, der ersetzte Text kann den Rest der Zeile überlappen; AdjustSpaceWidth - versucht, die Abstände zwischen den Wörtern anzupassen, um die Zeilenlänge beizubehalten; WholeWordsHyphenation - versucht, die Wörter zwischen den Absatzzeilen zu verteilen, um das rechte Feld des Absatzes zu behalten; ShiftRestOfLine - verschiebt den Rest der Zeile entsprechend der sich ändernden Textlänge, die Länge der Zeile kann sich ändern; Der Standardwert ist ShiftRestOfLine.
type: docs
weight: 11020
url: /de/net/aspose.pdf.text/textreplaceoptions.replaceadjustment/
---
## TextReplaceOptions.ReplaceAdjustment Aufzählung

Bestimmt die Aktion, die nach dem Ersetzen eines Textfragmentes durch einen kürzeren Text durchgeführt wird. None - keine Aktion, der ersetzte Text kann den Rest der Zeile überlappen; AdjustSpaceWidth - versucht, die Abstände zwischen den Wörtern anzupassen, um die Zeilenlänge beizubehalten; WholeWordsHyphenation - versucht, die Wörter zwischen den Absatzzeilen zu verteilen, um das rechte Feld des Absatzes zu behalten; ShiftRestOfLine - verschiebt den Rest der Zeile entsprechend der sich ändernden Textlänge, die Länge der Zeile kann sich ändern; Der Standardwert ist ShiftRestOfLine.

```csharp
[Flags]
public enum ReplaceAdjustment
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | `0` | Keine Aktion, der ersetzte Text kann den Rest der Zeile überlappen |
| AdjustSpaceWidth | `1` | Versucht, die Abstände zwischen den Wörtern anzupassen, um die Zeilenlänge beizubehalten |
| WholeWordsHyphenation | `2` | Versucht, die Wörter zwischen den Absatzzeilen zu verteilen, um das rechte Feld des Absatzes zu behalten |
| IsFormFillingMode | `4` | Versucht, die Wörter im verfügbaren weißen Raum unter Verwendung der Absatzbreite zu verteilen. Wenn der Text überläuft, wird er verborgen. |
| ShiftRestOfLine | `8` | (Standard) Verschiebt den Rest der Zeile entsprechend der sich ändernden Textlänge, die Länge der Zeile kann sich ändern |

### Siehe auch

* Klasse [TextReplaceOptions](../textreplaceoptions/)
* Namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../)