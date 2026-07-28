---
title: "PdfFormatConversionOptions.PdfANonSpecificationFlags"
linktitle: "PdfFormatConversionOptions.PdfANonSpecificationFlags"
second_title: "Aspose.PDF för Java API-referens"
description: "Denna klass innehåller flaggor för att kontrollera PDF/A‑konvertering i fall där källdokumentet PDF inte överensstämmer med PDF‑specifikationen. Om flaggorna i denna klass används minskar det."
type: docs
weight: 3740
url: /sv/java/com.aspose.pdf/pdfformatconversionoptions.pdfanonspecificationflags/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfFormatConversionOptions.PdfANonSpecificationFlags

```
public static class PdfFormatConversionOptions.PdfANonSpecificationFlags extends Object
```

Denna klass innehåller flaggor för att styra PDF/A-konvertering i fall då källdokumentet PDF inte överensstämmer med PDF-specifikationen. Om flaggorna i denna klass används minskar prestandan, men det är nödvändigt när källdokumentet PDF inte kan konverteras till PDF/A-format på vanligt sätt. Som standard är alla flaggor satta till false.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PdfANonSpecificationFlags](#PdfANonSpecificationFlags--) | Konstruktör |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCheckDifferentNamesInFontDictionaries](#getCheckDifferentNamesInFontDictionaries--) | Vissa PDF‑dokument innehåller teckensnitt som har olika namn i intern data. Användning av denna flagga tvingar fram speciell bearbetningslogik för fall där fälten BaseFont och FontDescriptor.FontName är olika. |
| [setCheckDifferentNamesInFontDictionaries](#setCheckDifferentNamesInFontDictionaries-boolean-) | Vissa PDF‑dokument innehåller teckensnitt som har olika namn i intern data. Användning av denna flagga tvingar fram speciell bearbetningslogik för fall där fälten BaseFont och FontDescriptor.FontName är olika. |

### PdfANonSpecificationFlags {#PdfANonSpecificationFlags--}
```
public PdfANonSpecificationFlags()
```

Konstruktör

### getCheckDifferentNamesInFontDictionaries {#getCheckDifferentNamesInFontDictionaries--}
```
public boolean getCheckDifferentNamesInFontDictionaries()
```

Vissa PDF‑dokument innehåller teckensnitt som har olika namn i intern data. Användning av denna flagga tvingar fram speciell bearbetningslogik för fall där fälten BaseFont och FontDescriptor.FontName är olika.

**Returns:**
booleskt värde

### setCheckDifferentNamesInFontDictionaries {#setCheckDifferentNamesInFontDictionaries-boolean-}
```
public void setCheckDifferentNamesInFontDictionaries(boolean value)
```

Vissa PDF‑dokument innehåller teckensnitt som har olika namn i intern data. Användning av denna flagga tvingar fram speciell bearbetningslogik för fall där fälten BaseFont och FontDescriptor.FontName är olika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
