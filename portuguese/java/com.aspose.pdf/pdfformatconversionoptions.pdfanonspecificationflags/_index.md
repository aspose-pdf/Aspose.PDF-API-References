---
title: "PdfFormatConversionOptions.PdfANonSpecificationFlags"
linktitle: "PdfFormatConversionOptions.PdfANonSpecificationFlags"
second_title: "Referência da API Aspose.PDF para Java"
description: "Esta classe contém flags para controlar a conversão PDF/A em casos em que o documento PDF de origem não corresponde à especificação PDF. Se as flags desta classe forem usadas, isso diminui."
type: docs
weight: 3740
url: /pt/java/com.aspose.pdf/pdfformatconversionoptions.pdfanonspecificationflags/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfFormatConversionOptions.PdfANonSpecificationFlags

```
public static class PdfFormatConversionOptions.PdfANonSpecificationFlags extends Object
```

Esta classe contém flags para controlar a conversão PDF/A em casos em que o documento PDF de origem não corresponde à especificação PDF. Se as flags desta classe forem usadas, o desempenho diminui, mas é necessário quando o documento PDF de origem não pode ser convertido para o formato PDF/A da maneira usual. Por padrão, todas as flags são definidas como false.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PdfANonSpecificationFlags](#PdfANonSpecificationFlags--) | Construtor |

## Métodos

| Método | Descrição |
| --- | --- |
| [getCheckDifferentNamesInFontDictionaries](#getCheckDifferentNamesInFontDictionaries--) | Alguns documentos PDF contêm fontes que têm nomes diferentes nos dados internos. O uso desta flag impõe lógica de processamento especial para casos em que os campos BaseFont e FontDescriptor.FontName são diferentes. |
| [setCheckDifferentNamesInFontDictionaries](#setCheckDifferentNamesInFontDictionaries-boolean-) | Alguns documentos PDF contêm fontes que têm nomes diferentes nos dados internos. O uso desta flag impõe lógica de processamento especial para casos em que os campos BaseFont e FontDescriptor.FontName são diferentes. |

### PdfANonSpecificationFlags {#PdfANonSpecificationFlags--}
```
public PdfANonSpecificationFlags()
```

Construtor

### getCheckDifferentNamesInFontDictionaries {#getCheckDifferentNamesInFontDictionaries--}
```
public boolean getCheckDifferentNamesInFontDictionaries()
```

Alguns documentos PDF contêm fontes que têm nomes diferentes nos dados internos. O uso desta flag impõe lógica de processamento especial para casos em que os campos BaseFont e FontDescriptor.FontName são diferentes.

**Returns:**
valor booleano

### setCheckDifferentNamesInFontDictionaries {#setCheckDifferentNamesInFontDictionaries-boolean-}
```
public void setCheckDifferentNamesInFontDictionaries(boolean value)
```

Alguns documentos PDF contêm fontes que têm nomes diferentes nos dados internos. O uso desta flag impõe lógica de processamento especial para casos em que os campos BaseFont e FontDescriptor.FontName são diferentes.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |
