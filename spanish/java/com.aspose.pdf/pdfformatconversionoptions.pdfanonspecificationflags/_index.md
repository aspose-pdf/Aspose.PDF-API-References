---
title: "PdfFormatConversionOptions.PdfANonSpecificationFlags"
linktitle: "PdfFormatConversionOptions.PdfANonSpecificationFlags"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Esta clase contiene banderas para controlar la conversión PDF/A en casos en que el documento PDF de origen no corresponde a la especificación PDF. Si se usan las banderas de esta clase, disminuye."
type: docs
weight: 3740
url: /es/java/com.aspose.pdf/pdfformatconversionoptions.pdfanonspecificationflags/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfFormatConversionOptions.PdfANonSpecificationFlags

```
public static class PdfFormatConversionOptions.PdfANonSpecificationFlags extends Object
```

Esta clase contiene banderas para controlar la conversión a PDF/A en los casos en que el documento PDF de origen no cumpla con la especificación PDF. Si se utilizan las banderas de esta clase, disminuye el rendimiento, pero es necesario cuando el documento PDF de origen no puede convertirse al formato PDF/A de manera habitual. Por defecto, todas las banderas están establecidas en false.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfANonSpecificationFlags](#PdfANonSpecificationFlags--) | Constructor |

## Métodos

| Método | Descripción |
| --- | --- |
| [getCheckDifferentNamesInFontDictionaries](#getCheckDifferentNamesInFontDictionaries--) | Algunos documentos PDF contienen fuentes que tienen nombres diferentes en los datos internos. El uso de esta bandera impone una lógica de procesamiento especial para los casos en que los campos BaseFont y FontDescriptor.FontName son diferentes. |
| [setCheckDifferentNamesInFontDictionaries](#setCheckDifferentNamesInFontDictionaries-boolean-) | Algunos documentos PDF contienen fuentes que tienen nombres diferentes en los datos internos. El uso de esta bandera impone una lógica de procesamiento especial para los casos en que los campos BaseFont y FontDescriptor.FontName son diferentes. |

### PdfANonSpecificationFlags {#PdfANonSpecificationFlags--}
```
public PdfANonSpecificationFlags()
```

Constructor

### getCheckDifferentNamesInFontDictionaries {#getCheckDifferentNamesInFontDictionaries--}
```
public boolean getCheckDifferentNamesInFontDictionaries()
```

Algunos documentos PDF contienen fuentes que tienen nombres diferentes en los datos internos. El uso de esta bandera impone una lógica de procesamiento especial para los casos en que los campos BaseFont y FontDescriptor.FontName son diferentes.

**Returns:**
valor booleano

### setCheckDifferentNamesInFontDictionaries {#setCheckDifferentNamesInFontDictionaries-boolean-}
```
public void setCheckDifferentNamesInFontDictionaries(boolean value)
```

Algunos documentos PDF contienen fuentes que tienen nombres diferentes en los datos internos. El uso de esta bandera impone una lógica de procesamiento especial para los casos en que los campos BaseFont y FontDescriptor.FontName son diferentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |
