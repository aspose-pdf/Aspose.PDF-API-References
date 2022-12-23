---
title: PdfFormatConversionOptions.PdfANonSpecificationFlags
second_title: Aspose.PDF for Java API Reference
description: This class holds flags to control PDF/A conversion for cases when source PDF document doesnt correspond to PDF specification.
type: docs
weight: 10
url: /java/com.aspose.pdf/pdfformatconversionoptions.pdfanonspecificationflags/
---
**Inheritance:**
java.lang.Object
```
public static class PdfFormatConversionOptions.PdfANonSpecificationFlags
```

This class holds flags to control PDF/A conversion for cases when source PDF document doesn't correspond to PDF specification. If flags of this clas are used it decreases performance but it's necessary when source PDF document can't be convert into PDF/A format by usual way. By default all flags are set to false.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfANonSpecificationFlags()](#PdfANonSpecificationFlags--) | Constructor |
## Methods

| Method | Description |
| --- | --- |
| [getCheckDifferentNamesInFontDictionaries()](#getCheckDifferentNamesInFontDictionaries--) | Some PDF documents contain fonts which have different names in internal data. |
| [setCheckDifferentNamesInFontDictionaries(boolean value)](#setCheckDifferentNamesInFontDictionaries-boolean-) | Some PDF documents contain fonts which have different names in internal data. |
### PdfANonSpecificationFlags() {#PdfANonSpecificationFlags--}
```
public PdfANonSpecificationFlags()
```


Constructor

### getCheckDifferentNamesInFontDictionaries() {#getCheckDifferentNamesInFontDictionaries--}
```
public boolean getCheckDifferentNamesInFontDictionaries()
```


Some PDF documents contain fonts which have different names in internal data. Use of this flag enforces special processing logic for cases when fields BaseFont and FontDescriptor.FontName are different.

**Returns:**
boolean - boolean value
### setCheckDifferentNamesInFontDictionaries(boolean value) {#setCheckDifferentNamesInFontDictionaries-boolean-}
```
public void setCheckDifferentNamesInFontDictionaries(boolean value)
```


Some PDF documents contain fonts which have different names in internal data. Use of this flag enforces special processing logic for cases when fields BaseFont and FontDescriptor.FontName are different.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

