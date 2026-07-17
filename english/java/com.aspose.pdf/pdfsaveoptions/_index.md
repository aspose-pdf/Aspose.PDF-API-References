---
title: PdfSaveOptions
linktitle: PdfSaveOptions
second_title: Aspose.PDF for Java API Reference
description: Save options for export to Pdf format
type: docs
weight: 3790
url: /java/com.aspose.pdf/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.PdfSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.PdfSaveOptions

```
public class PdfSaveOptions extends SaveOptions
```

Save options for export to Pdf format

## Constructors

| Constructor | Description |
| --- | --- |
| [PdfSaveOptions](#PdfSaveOptions--) | Constructor |

## Methods

| Method | Description |
| --- | --- |
| [getDefaultFontName](#getDefaultFontName--) | Font name used by default for fonts which are absent on computer. When the PDF document that is saved into PDF contains fonts, that are not available in the document itself and on the device, API replaces this fonts with the default font(if font with {@code DefaultFontName} is found on device) |
| [getTempPath](#getTempPath--) | Path for temporary files. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Font name used by default for fonts which are absent on computer. When the PDF document that is saved into PDF contains fonts, that are not available in the document itself and on the device, API replaces this fonts with the default font(if font with {@code DefaultFontName} is found on device) |
| [setTempPath](#setTempPath-java.lang.String-) | Path for temporary files. |

### PdfSaveOptions {#PdfSaveOptions--}
```
public PdfSaveOptions()
```

Constructor

### getDefaultFontName {#getDefaultFontName--}
```
public String getDefaultFontName()
```

Font name used by default for fonts which are absent on computer. When the PDF document that is saved into PDF contains fonts, that are not available in the document itself and on the device, API replaces this fonts with the default font(if font with {@code DefaultFontName} is found on device)

**Returns:**
String value

### getTempPath {#getTempPath--}
```
public final String getTempPath()
```

Path for temporary files.

**Returns:**
String value

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Font name used by default for fonts which are absent on computer. When the PDF document that is saved into PDF contains fonts, that are not available in the document itself and on the device, API replaces this fonts with the default font(if font with {@code DefaultFontName} is found on device)

### setTempPath {#setTempPath-java.lang.String-}
Path for temporary files.
