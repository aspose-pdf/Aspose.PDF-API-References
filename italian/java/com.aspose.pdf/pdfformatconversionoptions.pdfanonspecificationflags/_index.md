---
title: "PdfFormatConversionOptions.PdfANonSpecificationFlags"
linktitle: "PdfFormatConversionOptions.PdfANonSpecificationFlags"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Questa classe contiene flag per controllare la conversione PDF/A nei casi in cui il documento PDF di origine non corrisponda alla specifica PDF. Se i flag di questa classe vengono usati, diminuisce."
type: docs
weight: 3740
url: /it/java/com.aspose.pdf/pdfformatconversionoptions.pdfanonspecificationflags/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfFormatConversionOptions.PdfANonSpecificationFlags

```
public static class PdfFormatConversionOptions.PdfANonSpecificationFlags extends Object
```

Questa classe contiene flag per controllare la conversione PDF/A nei casi in cui il documento PDF di origine non corrisponda alla specifica PDF. Se i flag di questa classe vengono usati, le prestazioni diminuiscono, ma è necessario quando il documento PDF di origine non può essere convertito nel formato PDF/A in modo consueto. Per impostazione predefinita tutti i flag sono impostati su false.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfANonSpecificationFlags](#PdfANonSpecificationFlags--) | Costruttore |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCheckDifferentNamesInFontDictionaries](#getCheckDifferentNamesInFontDictionaries--) | Alcuni documenti PDF contengono font che hanno nomi diversi nei dati interni. L'uso di questo flag impone una logica di elaborazione speciale per i casi in cui i campi BaseFont e FontDescriptor.FontName siano diversi. |
| [setCheckDifferentNamesInFontDictionaries](#setCheckDifferentNamesInFontDictionaries-boolean-) | Alcuni documenti PDF contengono font che hanno nomi diversi nei dati interni. L'uso di questo flag impone una logica di elaborazione speciale per i casi in cui i campi BaseFont e FontDescriptor.FontName siano diversi. |

### PdfANonSpecificationFlags {#PdfANonSpecificationFlags--}
```
public PdfANonSpecificationFlags()
```

Costruttore

### getCheckDifferentNamesInFontDictionaries {#getCheckDifferentNamesInFontDictionaries--}
```
public boolean getCheckDifferentNamesInFontDictionaries()
```

Alcuni documenti PDF contengono font che hanno nomi diversi nei dati interni. L'uso di questo flag impone una logica di elaborazione speciale per i casi in cui i campi BaseFont e FontDescriptor.FontName siano diversi.

**Returns:**
valore booleano

### setCheckDifferentNamesInFontDictionaries {#setCheckDifferentNamesInFontDictionaries-boolean-}
```
public void setCheckDifferentNamesInFontDictionaries(boolean value)
```

Alcuni documenti PDF contengono font che hanno nomi diversi nei dati interni. L'uso di questo flag impone una logica di elaborazione speciale per i casi in cui i campi BaseFont e FontDescriptor.FontName siano diversi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |
