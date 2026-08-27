---
title: "PdfSaveOptions"
linktitle: "PdfSaveOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Spara alternativ för export till Pdf-format"
type: docs
weight: 3790
url: /sv/java/com.aspose.pdf/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.PdfSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.PdfSaveOptions

```
public class PdfSaveOptions extends SaveOptions
```

Spara alternativ för export till Pdf-format

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PdfSaveOptions](#PdfSaveOptions--) | Konstruktör |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDefaultFontName](#getDefaultFontName--) | Typsnittsnamn som används som standard för typsnitt som saknas på datorn. När PDF-dokumentet som sparas till PDF innehåller typsnitt som inte är tillgängliga i dokumentet självt och på enheten, ersätter API:et dessa typsnitt med standardtypsnittet (om ett typsnitt med {@code DefaultFontName} finns på enheten). |
| [getTempPath](#getTempPath--) | Sökväg för temporära filer. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Typsnittsnamn som används som standard för typsnitt som saknas på datorn. När PDF-dokumentet som sparas till PDF innehåller typsnitt som inte är tillgängliga i dokumentet självt och på enheten, ersätter API:et dessa typsnitt med standardtypsnittet (om ett typsnitt med {@code DefaultFontName} finns på enheten). |
| [setTempPath](#setTempPath-java.lang.String-) | Sökväg för temporära filer. |

### PdfSaveOptions {#PdfSaveOptions--}
```
public PdfSaveOptions()
```

Konstruktör

### getDefaultFontName {#getDefaultFontName--}
```
public String getDefaultFontName()
```

Typsnittsnamn som används som standard för typsnitt som saknas på datorn. När PDF-dokumentet som sparas till PDF innehåller typsnitt som inte är tillgängliga i dokumentet självt och på enheten, ersätter API:et dessa typsnitt med standardtypsnittet (om ett typsnitt med {@code DefaultFontName} finns på enheten).

**Returns:**
String värde

### getTempPath {#getTempPath--}
```
public final String getTempPath()
```

Sökväg för temporära filer.

**Returns:**
String värde

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Typsnittsnamn som används som standard för typsnitt som saknas på datorn. När PDF-dokumentet som sparas till PDF innehåller typsnitt som inte är tillgängliga i dokumentet självt och på enheten, ersätter API:et dessa typsnitt med standardtypsnittet (om ett typsnitt med {@code DefaultFontName} finns på enheten).

### setTempPath {#setTempPath-java.lang.String-}
Sökväg för temporära filer.
