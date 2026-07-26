---
title: "PdfFormatConversionOptions.PuaProcessingStrategy"
linktitle: "PdfFormatConversionOptions.PuaProcessingStrategy"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Einige PDF-Dokumente enthalten spezielle Unicode‑Symbole, die zum Private‑Use‑Area (PUA) gehören, siehe Beschreibung unter https://en.wikipedia.org/wiki/Private_Use_Areas. Diese Symbole."
type: docs
weight: 3750
url: /de/java/com.aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy

```
public static final class PdfFormatConversionOptions.PuaProcessingStrategy extends com.aspose.ms.System.Enum
```

Einige PDF-Dokumente enthalten spezielle Unicode‑Symbole, die zum Private Use Area (PUA) gehören; siehe Beschreibung unter https://en.wikipedia.org/wiki/Private_Use_Areas. Diese Symbole verursachen PDF/A‑konforme Fehler wie „Text ist dem Unicode Private Use Area zugeordnet, aber kein ActualText‑Eintrag ist vorhanden“. Diese Aufzählung deklariert Strategien, die zum Umgang mit PUA‑Symbolen verwendet werden können.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [None](#None) | Deaktiviert die Verarbeitung von PUA‑Symbolen. Diese Strategie wird standardmäßig für PDF/A‑Dokumente mit Level‑B‑Konformität verwendet. |
| [SubstitutePuaSymbols](#SubstitutePuaSymbols) | Diese Strategie arbeitet langsamer als 'SurroundPuaTextWithEmptyActualText', kann jedoch PUA‑konforme Fehler bei Dokumenten entfernen, die nicht korrekt von SurroundPuaTextWithEmptyActualText verarbeitet werden können. PUA‑Symbole werden durch das Symbol 'space' oder spezielles Unicode ersetzt (einige PUA‑Symbole haben Unicode‑Analoga). Die Substitution wird nicht auf den Text des Dokuments, sondern auf die interne Font‑Daten‑ToUnicode angewendet, sodass sie die Sichtbarkeit des Symbols nicht beeinträchtigt, aber die Darstellung des Symbols beim Kopieren/Einfügen im Systempuffer beeinflusst. |
| [SurroundPuaTextWithEmptyActualText](#SurroundPuaTextWithEmptyActualText) | Fügt einen markierten Inhaltsblock mit ActualText‑Eintrag ein, der leeren Text enthält. Diese Strategie liefert gute Ergebnisse für Dokumente ohne markierte Inhaltsblöcke. Wird standardmäßig für PDF/A‑Dokumente mit Level‑A‑Konformität verwendet. |

### None {#None}
```
public static final int None
```

Deaktiviert die Verarbeitung von PUA‑Symbolen. Diese Strategie wird standardmäßig für PDF/A‑Dokumente mit Level‑B‑Konformität verwendet.

### SubstitutePuaSymbols {#SubstitutePuaSymbols}
```
public static final int SubstitutePuaSymbols
```

Diese Strategie arbeitet langsamer als 'SurroundPuaTextWithEmptyActualText', kann jedoch PUA‑konforme Fehler bei Dokumenten entfernen, die nicht korrekt von SurroundPuaTextWithEmptyActualText verarbeitet werden können. PUA‑Symbole werden durch das Symbol 'space' oder spezielles Unicode ersetzt (einige PUA‑Symbole haben Unicode‑Analoga). Die Substitution wird nicht auf den Text des Dokuments, sondern auf die interne Font‑Daten‑ToUnicode angewendet, sodass sie die Sichtbarkeit des Symbols nicht beeinträchtigt, aber die Darstellung des Symbols beim Kopieren/Einfügen im Systempuffer beeinflusst.

### SurroundPuaTextWithEmptyActualText {#SurroundPuaTextWithEmptyActualText}
```
public static final int SurroundPuaTextWithEmptyActualText
```

Fügt einen markierten Inhaltsblock mit ActualText‑Eintrag ein, der leeren Text enthält. Diese Strategie liefert gute Ergebnisse für Dokumente ohne markierte Inhaltsblöcke. Wird standardmäßig für PDF/A‑Dokumente mit Level‑A‑Konformität verwendet.
