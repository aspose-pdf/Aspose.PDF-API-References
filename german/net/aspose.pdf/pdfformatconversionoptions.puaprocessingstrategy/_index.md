---
title: Enum PdfFormatConversionOptions.PuaProcessingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfFormatConversionOptionsPuaProcessingStrategy Enum. Einige PDF-Dokumente enthalten spezielle Unicode-Symbole, die zum Private Use Area (PUA) gehören, siehe Beschreibung unter https//de.wikipedia.org/wiki/Private_Use_Areas. Diese Symbole verursachen PDF/A-konforme Fehler wie "Text ist auf den Unicode Private Use Area abgebildet, aber kein ActualText-Eintrag ist vorhanden". Diese Enumeration erklärt Strategien, die verwendet werden können, um PUA-Symbole zu behandeln.
type: docs
weight: 8390
url: /de/net/aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
## PdfFormatConversionOptions.PuaProcessingStrategy Enumeration

Einige PDF-Dokumente enthalten spezielle Unicode-Symbole, die zum Private Use Area (PUA) gehören, siehe Beschreibung unter https://en.wikipedia.org/wiki/Private_Use_Areas. Diese Symbole verursachen PDF/A-konforme Fehler wie "Text ist auf den Unicode Private Use Area abgebildet, aber kein ActualText-Eintrag ist vorhanden". Diese Enumeration erklärt Strategien, die verwendet werden können, um PUA-Symbole zu behandeln.

```csharp
public enum PuaProcessingStrategy
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | `0` | Deaktiviert die Verarbeitung von PUA-Symbolen. Diese Strategie wird standardmäßig für PDF/A-Dokumente mit Level B-Konformität verwendet. |
| SurroundPuaTextWithEmptyActualText | `1` | Fügt einen markierten Inhaltsblock mit einem ActualText-Eintrag ein, der leeren Text enthält. Diese Strategie liefert gute Ergebnisse für Dokumente ohne markierte Inhaltsblöcke. Wird standardmäßig für PDF/A-Dokumente mit Level A-Konformität verwendet. |
| SubstitutePuaSymbols | `2` | Diese Strategie arbeitet langsamer als 'SurroundPuaTextWithEmptyActualText', kann jedoch PUA-konforme Fehler für Dokumente entfernen, die von SurroundPuaTextWithEmptyActualText nicht ordnungsgemäß behandelt werden können. PUA-Symbole werden durch das Symbol 'space' oder spezielle Unicode ersetzt (einige PUA-Symbole haben Unicode-Analoga). Die Substitution wird nicht auf den Text des Dokuments, sondern auf die internen Daten der Schriftart ToUnicode angewendet, sodass sie die Sichtbarkeit des Symbols nicht beeinflusst, aber die Präsentation des Symbols im Kopier-/Einfüge-Betriebssystempuffer beeinflusst. |

### Siehe auch

* Klasse [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)