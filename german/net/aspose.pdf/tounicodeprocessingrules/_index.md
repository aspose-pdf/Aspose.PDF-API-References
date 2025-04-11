---
title: Class ToUnicodeProcessingRules
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ToUnicodeProcessingRules-Klasse. Diese Klasse beschreibt Regeln, die verwendet werden können, um den Adobe Preflight-Fehler "Text kann nicht in Unicode abgebildet werden" zu lösen.
type: docs
weight: 11110
url: /de/net/aspose.pdf/tounicodeprocessingrules/
---
## ToUnicodeProcessingRules-Klasse

Diese Klasse beschreibt Regeln, die verwendet werden können, um den Adobe Preflight-Fehler "Text kann nicht in Unicode abgebildet werden" zu lösen.

```csharp
public class ToUnicodeProcessingRules
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor)() | Initialisiert eine neue Instanz der `ToUnicodeProcessingRules`-Klasse. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_1)(bool) | Initialisiert eine neue Instanz der `ToUnicodeProcessingRules`-Klasse mit der angegebenen Option, um Leerzeichen aus CMap-Namen zu entfernen. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_2)(bool, bool) | Initialisiert eine neue Instanz der `ToUnicodeProcessingRules`-Klasse mit angegebenen Optionen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [MapNonLinkedSymbolsOnSpace](../../aspose.pdf/tounicodeprocessingrules/mapnonlinkedsymbolsonspace/) { get; set; } | Einige Schriftarten bieten keine Informationen über Unicodes für einige Textsymbole. Dieser Mangel an Informationen verursacht einen Fehler "Text kann nicht in Unicode abgebildet werden". Verwenden Sie dieses Flag, um nicht verlinkte Symbole auf Unicode "Leerzeichen" (Code 32) abzubilden. |
| [RemoveSpacesFromCMapNames](../../aspose.pdf/tounicodeprocessingrules/removespacesfromcmapnames/) { get; set; } | Einige Schriftarten haben ToUnicode-Zeichencode-Tabellen mit Leerzeichen in den Namen. Diese Leerzeichen könnten Fehler bei der Unicode-Textabbildung verursachen. Dieses Flag weist an, Leerzeichen aus den Namen der ToUnicode-Zeichencode-Tabellen zu entfernen. Standardmäßig false. |

### Siehe auch

* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)