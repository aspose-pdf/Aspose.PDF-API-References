---
title: "PdfFormatConversionOptions.PdfANonSpecificationFlags"
linktitle: "PdfFormatConversionOptions.PdfANonSpecificationFlags"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Cette classe contient des indicateurs pour contrôler la conversion PDF/A dans les cas où le document PDF source ne correspond pas à la spécification PDF. Si les indicateurs de cette classe sont utilisés, cela diminue."
type: docs
weight: 3740
url: /fr/java/com.aspose.pdf/pdfformatconversionoptions.pdfanonspecificationflags/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfFormatConversionOptions.PdfANonSpecificationFlags

```
public static class PdfFormatConversionOptions.PdfANonSpecificationFlags extends Object
```

Cette classe contient des indicateurs pour contrôler la conversion PDF/A dans les cas où le document PDF source ne correspond pas à la spécification PDF. Si les indicateurs de cette classe sont utilisés, cela diminue les performances mais c'est nécessaire lorsque le document PDF source ne peut pas être converti au format PDF/A de manière habituelle. Par défaut, tous les indicateurs sont définis sur false.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfANonSpecificationFlags](#PdfANonSpecificationFlags--) | Constructeur |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getCheckDifferentNamesInFontDictionaries](#getCheckDifferentNamesInFontDictionaries--) | Certains documents PDF contiennent des polices dont les noms diffèrent dans les données internes. L'utilisation de cet indicateur impose une logique de traitement spéciale pour les cas où les champs BaseFont et FontDescriptor.FontName sont différents. |
| [setCheckDifferentNamesInFontDictionaries](#setCheckDifferentNamesInFontDictionaries-boolean-) | Certains documents PDF contiennent des polices dont les noms diffèrent dans les données internes. L'utilisation de cet indicateur impose une logique de traitement spéciale pour les cas où les champs BaseFont et FontDescriptor.FontName sont différents. |

### PdfANonSpecificationFlags {#PdfANonSpecificationFlags--}
```
public PdfANonSpecificationFlags()
```

Constructeur

### getCheckDifferentNamesInFontDictionaries {#getCheckDifferentNamesInFontDictionaries--}
```
public boolean getCheckDifferentNamesInFontDictionaries()
```

Certains documents PDF contiennent des polices dont les noms diffèrent dans les données internes. L'utilisation de cet indicateur impose une logique de traitement spéciale pour les cas où les champs BaseFont et FontDescriptor.FontName sont différents.

**Returns:**
valeur booléenne

### setCheckDifferentNamesInFontDictionaries {#setCheckDifferentNamesInFontDictionaries-boolean-}
```
public void setCheckDifferentNamesInFontDictionaries(boolean value)
```

Certains documents PDF contiennent des polices dont les noms diffèrent dans les données internes. L'utilisation de cet indicateur impose une logique de traitement spéciale pour les cas où les champs BaseFont et FontDescriptor.FontName sont différents.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
