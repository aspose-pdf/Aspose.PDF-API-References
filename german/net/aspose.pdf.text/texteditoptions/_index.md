---
title: TextEditOptions
second_title: Aspose.PDF für .NET-API-Referenz
description: Beschreibt Optionen für Textbearbeitungsvorgänge.
type: docs
weight: 6980
url: /de/net/aspose.pdf.text/texteditoptions/
---
## TextEditOptions class

Beschreibt Optionen für Textbearbeitungsvorgänge.

```csharp
public sealed class TextEditOptions : TextOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [TextEditOptions](texteditoptions#constructor)(bool) | Initialisiert eine neue Instanz von[`TextEditOptions`](../texteditoptions) Objekt für die angegebene Sprachumwandlungsberechtigung. |
| [TextEditOptions](texteditoptions#constructor_1)(FontReplace) | Initialisiert eine neue Instanz von[`TextEditOptions`](../texteditoptions) Objekt für den angegebenen Verhaltensmodus zum Ersetzen von Schriftarten. |
| [TextEditOptions](texteditoptions#constructor_2)(LanguageTransformation) | Initialisiert eine neue Instanz von[`TextEditOptions`](../texteditoptions) Objekt für den angegebenen Sprachumwandlungsverhaltensmodus. |
| [TextEditOptions](texteditoptions#constructor_3)(NoCharacterAction) | Initialisiert eine neue Instanz von[`TextEditOptions`](../texteditoptions) Objekt für den angegebenen zeichenlosen Verhaltensmodus. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AllowLanguageTransformation](../../aspose.pdf.text/texteditoptions/allowlanguagetransformation) { get; set; } | Ruft einen Wert ab oder legt ihn fest, der die Verwendung der Sprachumwandlung beim Hinzufügen oder Bearbeiten von Text zulässt. true – Sprachumwandlung wird angewendet, falls erforderlich (Standardwert). false – Sprachumwandlung wird NICHT angewendet. |
| [ClippingPathsProcessing](../../aspose.pdf.text/texteditoptions/clippingpathsprocessing) { get; set; } | Ruft den Modus zum Verarbeiten des Beschneidungspfads des bearbeiteten Textes ab. |
| [FontReplaceBehavior](../../aspose.pdf.text/texteditoptions/fontreplacebehavior) { get; set; } | Ruft den Modus ab, der das Verhalten für Schriftartersetzungsszenarien definiert. |
| [LanguageTransformationBehavior](../../aspose.pdf.text/texteditoptions/languagetransformationbehavior) { get; set; } | Ruft den Modus ab, der das Verhalten für Sprachtransformationsszenarien definiert. |
| [NoCharacterBehavior](../../aspose.pdf.text/texteditoptions/nocharacterbehavior) { get; set; } | Ruft den Modus ab oder legt ihn fest, der das Verhalten definiert, falls Schriftarten die angeforderten Zeichen nicht enthalten. |
| [ReplacementFont](../../aspose.pdf.text/texteditoptions/replacementfont) { get; set; } | Ruft die Schriftart ab oder legt sie fest, die zum Ersetzen verwendet wird, wenn die Benutzerschriftart das erforderliche Zeichen nicht enthält |
| [ToAttemptGetUnderlineFromSource](../../aspose.pdf.text/texteditoptions/toattemptgetunderlinefromsource) { get; set; } | Erhält oder setzt einen Wert, der die Suche nach unterstrichenem Text auf der Seite des Quelldokuments erlaubt. (veraltet) Bitte verwenden Sie stattdessen TextSearchOptions.SearchForTextRelatedGraphics. |

### Siehe auch

* class [TextOptions](../textoptions)
* namensraum [Aspose.Pdf.Text](../../aspose.pdf.text)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
