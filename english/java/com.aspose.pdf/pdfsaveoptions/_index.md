---
title: PdfSaveOptions
second_title: Aspose.PDF for Java API Reference
description: Save options for export to Pdf format
type: docs
weight: 283
url: /java/com.aspose.pdf/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.SaveOptions](../../com.aspose.pdf/saveoptions)
```
public class PdfSaveOptions extends SaveOptions
```

Save options for export to Pdf format
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) | Constructor |
## Methods

| Method | Description |
| --- | --- |
| [getTempPath()](#getTempPath--) | Path for temporary files. |
| [setTempPath(String value)](#setTempPath-java.lang.String-) | Path for temporary files. |
| [getDefaultFontName()](#getDefaultFontName--) | Font name used by default for fonts which are absent on computer. |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Font name used by default for fonts which are absent on computer. |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


Constructor

### getTempPath() {#getTempPath--}
```
public final String getTempPath()
```


Path for temporary files.

**Returns:**
java.lang.String - String value
### setTempPath(String value) {#setTempPath-java.lang.String-}
```
public final void setTempPath(String value)
```


Path for temporary files.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getDefaultFontName() {#getDefaultFontName--}
```
public String getDefaultFontName()
```


Font name used by default for fonts which are absent on computer. When the PDF document that is saved into PDF contains fonts, that are not available in the document itself and on the device, API replaces this fonts with the default font(if font with  DefaultFontName  is found on device)

**Returns:**
java.lang.String - String value
### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public void setDefaultFontName(String value)
```


Font name used by default for fonts which are absent on computer. When the PDF document that is saved into PDF contains fonts, that are not available in the document itself and on the device, API replaces this fonts with the default font(if font with  DefaultFontName  is found on device)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

