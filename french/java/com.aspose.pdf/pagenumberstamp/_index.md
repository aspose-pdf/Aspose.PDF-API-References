---
title: "PageNumberStamp"
linktitle: "PageNumberStamp"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente le tampon du numéro de page et est utilisé pour numéroter les pages."
type: docs
weight: 3440
url: /fr/java/com.aspose.pdf/pagenumberstamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.TextStamp com.aspose.pdf.PageNumberStamp, com.aspose.pdf.Stamp, com.aspose.pdf.TextStamp com.aspose.pdf.PageNumberStamp, com.aspose.pdf.TextStamp, com.aspose.pdf.PageNumberStamp

```
public final class PageNumberStamp extends TextStamp
```

Représente le tampon du numéro de page et est utilisé pour numéroter les pages.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PageNumberStamp](#PageNumberStamp--) | Initialise une nouvelle instance de la classe {@code PageNumberStamp}. Le format est défini sur "#". |
| [PageNumberStamp](#PageNumberStamp-com.aspose.pdf.facades.FormattedText-) | Initialise une nouvelle instance de la classe {@code PageNumberStamp}. Le format est défini sur "#". |
| [PageNumberStamp](#PageNumberStamp-java.lang.String-) | Initialise une nouvelle instance de la classe {@code PageNumberStamp}. Le format est défini sur "#". |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getFormat](#getFormat--) | Obtient la valeur String pour le tamponnage des numéros de page. La valeur doit inclure le caractère '#' qui est remplacé par le numéro de page lors du tamponnage. |
| [getNumberingStyle](#getNumberingStyle--) | Style de numérotation utilisé par ce tampon. |
| [getStartingNumber](#getStartingNumber--) | Obtient la valeur du numéro de la page de départ. Les autres pages seront numérotées à partir de cette valeur. |
| [put](#put-com.aspose.pdf.Page-) | Ajoute le numéro de page. |
| [setFormat](#setFormat-java.lang.String-) | Définit la valeur de type String pour le filigrane des numéros de page. La valeur doit inclure le caractère '#' qui est remplacé par le numéro de page lors du filigrane. |
| [setNumberingStyle](#setNumberingStyle-com.aspose.pdf.NumberingStyle-) | Style de numérotation utilisé par ce tampon. |
| [setStartingNumber](#setStartingNumber-int-) | Définit la valeur du numéro de la page de départ. Les autres pages seront numérotées à partir de cette valeur. |

### PageNumberStamp {#PageNumberStamp--}
```
public PageNumberStamp()
```

Initialise une nouvelle instance de la classe {@code PageNumberStamp}. Le format est défini sur "#".

### PageNumberStamp {#PageNumberStamp-com.aspose.pdf.facades.FormattedText-}
Initialise une nouvelle instance de la classe {@code PageNumberStamp}. Le format est défini sur "#".

### PageNumberStamp {#PageNumberStamp-java.lang.String-}
Initialise une nouvelle instance de la classe {@code PageNumberStamp}. Le format est défini sur "#".

### getFormat {#getFormat--}
```
public String getFormat()
```

Obtient la valeur String pour le tamponnage des numéros de page. La valeur doit inclure le caractère '#' qui est remplacé par le numéro de page lors du tamponnage.

**Returns:**
valeur String

### getNumberingStyle {#getNumberingStyle--}
```
public NumberingStyle getNumberingStyle()
```

Style de numérotation utilisé par ce tampon.

**Returns:**
Valeur NumberingStyle @see NumberingStyle

### getStartingNumber {#getStartingNumber--}
```
public int getStartingNumber()
```

Obtient la valeur du numéro de la page de départ. Les autres pages seront numérotées à partir de cette valeur.

**Returns:**
valeur int

### put {#put-com.aspose.pdf.Page-}
Ajoute le numéro de page.

### setFormat {#setFormat-java.lang.String-}
Définit la valeur de type String pour le filigrane des numéros de page. La valeur doit inclure le caractère '#' qui est remplacé par le numéro de page lors du filigrane.

### setNumberingStyle {#setNumberingStyle-com.aspose.pdf.NumberingStyle-}
Style de numérotation utilisé par ce tampon.

### setStartingNumber {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```

Définit la valeur du numéro de la page de départ. Les autres pages seront numérotées à partir de cette valeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |
