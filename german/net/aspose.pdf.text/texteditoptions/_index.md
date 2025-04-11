---
title: Class TextEditOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextEditOptions-Klasse. Beschreibt Optionen für Textbearbeitungsoperationen
type: docs
weight: 10820
url: /de/net/aspose.pdf.text/texteditoptions/
---
## TextEditOptions-Klasse

Beschreibt Optionen für Textbearbeitungsoperationen.

```csharp
public sealed class TextEditOptions : TextOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextEditOptions](texteditoptions/#constructor)(bool) | Initialisiert eine neue Instanz des `TextEditOptions`-Objekts für die angegebene Berechtigung zur Sprachtransformation. |
| [TextEditOptions](texteditoptions/#constructor_1)(FontReplace) | Initialisiert eine neue Instanz des `TextEditOptions`-Objekts für den angegebenen Modus des Schriftartenersatzverhaltens. |
| [TextEditOptions](texteditoptions/#constructor_2)(LanguageTransformation) | Initialisiert eine neue Instanz des `TextEditOptions`-Objekts für den angegebenen Modus des Verhaltens bei Sprachtransformation. |
| [TextEditOptions](texteditoptions/#constructor_3)(NoCharacterAction) | Initialisiert eine neue Instanz des `TextEditOptions`-Objekts für den angegebenen Modus des Verhaltens bei fehlenden Zeichen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AllowLanguageTransformation](../../aspose.pdf.text/texteditoptions/allowlanguagetransformation/) { get; set; } | Ruft den Wert ab oder legt ihn fest, der die Verwendung der Sprachtransformation beim Hinzufügen oder Bearbeiten von Text erlaubt. true - Sprachtransformation wird angewendet, wenn nötig (Standardwert). false - Sprachtransformation wird NICHT angewendet. |
| [ClippingPathsProcessing](../../aspose.pdf.text/texteditoptions/clippingpathsprocessing/) { get; set; } | Ruft den Modus für die Verarbeitung des Clipping-Pfades des bearbeiteten Textes ab. |
| [FontReplaceBehavior](../../aspose.pdf.text/texteditoptions/fontreplacebehavior/) { get; set; } | Ruft den Modus ab, der das Verhalten für Szenarien des Schriftartenersatzes definiert. |
| [LanguageTransformationBehavior](../../aspose.pdf.text/texteditoptions/languagetransformationbehavior/) { get; set; } | Ruft den Modus ab, der das Verhalten für Szenarien der Sprachtransformation definiert. |
| [NoCharacterBehavior](../../aspose.pdf.text/texteditoptions/nocharacterbehavior/) { get; set; } | Ruft den Modus ab oder legt ihn fest, der das Verhalten definiert, falls Schriftarten die angeforderten Zeichen nicht enthalten. |
| [ReplacementFont](../../aspose.pdf.text/texteditoptions/replacementfont/) { get; set; } | Ruft die Schriftart ab oder legt sie fest, die für den Ersatz verwendet wird, wenn die Benutzer-Schriftart das erforderliche Zeichen nicht enthält. |
| [ToAttemptGetUnderlineFromSource](../../aspose.pdf.text/texteditoptions/toattemptgetunderlinefromsource/) { get; set; } | Ruft den Wert ab oder legt ihn fest, der die Suche nach Textunterstreichungen auf der Seite des Quelldokuments erlaubt. (Veraltet) Bitte verwenden Sie stattdessen TextSearchOptions.SearchForTextRelatedGraphics. |

### Siehe auch

* Klasse [TextOptions](../textoptions/)
* Namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../)