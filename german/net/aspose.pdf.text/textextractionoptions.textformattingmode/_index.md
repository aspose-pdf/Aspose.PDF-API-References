---
title: Enum TextExtractionOptions.TextFormattingMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextExtractionOptionsTextFormattingMode Enum. Definiert verschiedene Modi, die beim Konvertieren eines PDF-Dokuments in Text verwendet werden können. Siehe TextDevice-Klasse
type: docs
weight: 10900
url: /de/net/aspose.pdf.text/textextractionoptions.textformattingmode/
---
## TextExtractionOptions.TextFormattingMode Aufzählung

Definiert verschiedene Modi, die beim Konvertieren eines PDF-Dokuments in Text verwendet werden können. Siehe !:TextDevice-Klasse.

```csharp
public enum TextFormattingMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Pure | `0` | Stellt PDF-Inhalt mit einer gewissen Formatierungsroutine dar. |
| Raw | `1` | Stellt PDF-Inhalt so dar, wie er ist, d.h. ohne Formatierung. |
| Flatten | `2` | Stellt PDF-Inhalt dar, indem Textfragmente nach ihren Koordinaten positioniert werden. Es ist im Grunde ähnlich wie der "Raw"-Modus. Während "Raw" sich darauf konzentriert, die Struktur von Textfragmenten (Operatoren) in einem Dokument zu bewahren, konzentriert sich "Flatten" darauf, den Text in der Reihenfolge zu halten, in der er gelesen wird. |
| MemorySaving | `3` | Extraktion mit Speicherersparnis. Es ist fast dasselbe wie der 'Raw'-Modus, funktioniert jedoch etwas schneller und verwendet weniger Speicher. |

### Siehe auch

* Klasse [TextExtractionOptions](../textextractionoptions/)
* Namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../)