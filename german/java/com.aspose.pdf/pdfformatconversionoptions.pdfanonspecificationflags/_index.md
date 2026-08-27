---
title: "PdfFormatConversionOptions.PdfANonSpecificationFlags"
linktitle: "PdfFormatConversionOptions.PdfANonSpecificationFlags"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Diese Klasse enthält Flags zur Steuerung der PDF/A-Konvertierung für Fälle, in denen das Quell‑PDF‑Dokument nicht der PDF‑Spezifikation entspricht. Wenn die Flags dieser Klasse verwendet werden, reduziert sich dies."
type: docs
weight: 3740
url: /de/java/com.aspose.pdf/pdfformatconversionoptions.pdfanonspecificationflags/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfFormatConversionOptions.PdfANonSpecificationFlags

```
public static class PdfFormatConversionOptions.PdfANonSpecificationFlags extends Object
```

Diese Klasse enthält Flags zur Steuerung der PDF/A-Konvertierung für Fälle, in denen das Quell-PDF-Dokument nicht der PDF-Spezifikation entspricht. Wenn die Flags dieser Klasse verwendet werden, verringert sich die Leistung, aber sie sind notwendig, wenn das Quell-PDF-Dokument nicht auf herkömmliche Weise in das PDF/A-Format konvertiert werden kann. Standardmäßig sind alle Flags auf false gesetzt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfANonSpecificationFlags](#PdfANonSpecificationFlags--) | Konstruktor |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCheckDifferentNamesInFontDictionaries](#getCheckDifferentNamesInFontDictionaries--) | Einige PDF‑Dokumente enthalten Schriftarten, die in den internen Daten unterschiedliche Namen haben. Die Verwendung dieses Flags erzwingt eine spezielle Verarbeitungslogik für Fälle, in denen die Felder BaseFont und FontDescriptor.FontName unterschiedlich sind. |
| [setCheckDifferentNamesInFontDictionaries](#setCheckDifferentNamesInFontDictionaries-boolean-) | Einige PDF‑Dokumente enthalten Schriftarten, die in den internen Daten unterschiedliche Namen haben. Die Verwendung dieses Flags erzwingt eine spezielle Verarbeitungslogik für Fälle, in denen die Felder BaseFont und FontDescriptor.FontName unterschiedlich sind. |

### PdfANonSpecificationFlags {#PdfANonSpecificationFlags--}
```
public PdfANonSpecificationFlags()
```

Konstruktor

### getCheckDifferentNamesInFontDictionaries {#getCheckDifferentNamesInFontDictionaries--}
```
public boolean getCheckDifferentNamesInFontDictionaries()
```

Einige PDF‑Dokumente enthalten Schriftarten, die in den internen Daten unterschiedliche Namen haben. Die Verwendung dieses Flags erzwingt eine spezielle Verarbeitungslogik für Fälle, in denen die Felder BaseFont und FontDescriptor.FontName unterschiedlich sind.

**Returns:**
boolescher Wert

### setCheckDifferentNamesInFontDictionaries {#setCheckDifferentNamesInFontDictionaries-boolean-}
```
public void setCheckDifferentNamesInFontDictionaries(boolean value)
```

Einige PDF‑Dokumente enthalten Schriftarten, die in den internen Daten unterschiedliche Namen haben. Die Verwendung dieses Flags erzwingt eine spezielle Verarbeitungslogik für Fälle, in denen die Felder BaseFont und FontDescriptor.FontName unterschiedlich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |
