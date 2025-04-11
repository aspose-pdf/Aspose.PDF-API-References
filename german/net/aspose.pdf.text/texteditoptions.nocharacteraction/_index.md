---
title: Enum TextEditOptions.NoCharacterAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextEditOptionsNoCharacterAction Enum. Aktion, die ausgeführt werden soll, wenn die Schriftart das erforderliche Zeichen nicht enthält
type: docs
weight: 10860
url: /de/net/aspose.pdf.text/texteditoptions.nocharacteraction/
---
## TextEditOptions.NoCharacterAction Aufzählung

Aktion, die ausgeführt werden soll, wenn die Schriftart das erforderliche Zeichen nicht enthält

```csharp
public enum NoCharacterAction
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| ThrowException | `0` | Ausnahme auslösen |
| UseStandardFont | `1` | Schriftart durch Standard-Schriftart ersetzen, die das erforderliche Zeichen enthält |
| ReplaceAnyway | `2` | Text trotzdem ersetzen, ohne Schriftartsubstitution |
| ReplaceFonts | `3` | Ersetzt Schriftarten nach Bedarf, um sicherzustellen, dass alle Zeichen im Text angezeigt werden können. Der Algorithmus zur Schriftartsubstitution folgt diesen Schritten: 1. Wenn der Benutzer die Schriftart-Eigenschaft ausdrücklich festlegt, überprüfen Sie, ob die angegebene Schriftart die gewünschten Zeichen anzeigen kann. 2. Wenn keine benutzerdefinierte Schriftart festgelegt ist, suchen Sie nach Schriftarten, die über die [`Sources`](../fontrepository/sources/) hinzugefügt wurden. 3. Analysieren Sie den Text, um sein Alphabet oder seine Schrift zu identifizieren und schlagen Sie entsprechende Schriftartnamen vor. Versuchen Sie, diese Schriftarten im System zu finden und zu verwenden. 4. Als Fallback suchen Sie im System nach einer Schriftart, die in der Lage ist, die erforderlichen Zeichen anzuzeigen. |
| UseCustomReplacementFont | `4` | Schriftart durch definierte Ersatzschriftart ersetzen |

### Siehe auch

* Klasse [TextEditOptions](../texteditoptions/)
* Namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../)