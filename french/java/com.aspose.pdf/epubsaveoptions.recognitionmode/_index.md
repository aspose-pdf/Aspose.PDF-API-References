---
title: "EpubSaveOptions.RecognitionMode"
linktitle: "EpubSaveOptions.RecognitionMode"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Lorsque le fichier PDF (qui a généralement une mise en page fixe) est converti, le moteur de conversion tente d'effectuer un regroupement et une analyse à plusieurs niveaux pour restaurer le document original."
type: docs
weight: 1250
url: /fr/java/com.aspose.pdf/epubsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < EpubSaveOptions.RecognitionMode > com.aspose.pdf.EpubSaveOptions.RecognitionMode, java.lang.Enum < EpubSaveOptions.RecognitionMode >, com.aspose.pdf.EpubSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < EpubSaveOptions.RecognitionMode >

```
public static enum EpubSaveOptions.RecognitionMode extends Enum < EpubSaveOptions.RecognitionMode >
```

Lorsque le fichier PDF (qui a généralement une mise en page fixe) est converti, le moteur de conversion tente d'effectuer un groupement et une analyse à plusieurs niveaux afin de restaurer l'intention de l'auteur du document original et de produire un résultat en mise en page fluide. Cette propriété ajuste cette conversion pour telle ou telle méthode souhaitée de reconnaissance du contenu.

## Champs

| Champ | Description |
| --- | --- |
| [Fixed](#Fixed) | Ce mode est rapide et bon pour préserver au maximum l'apparence originale des pages, mais malheureusement de nombreux lecteurs EPUB ne prennent pas en charge le xhtml à mise en page fixe |
| [Flow](#Flow) | Mode de reconnaissance complète, le moteur tente d'effectuer le regroupement et une analyse à plusieurs niveaux pour restaurer l'intention de l'auteur du document original et produire du xhtml en mise en page fluide. |
| [PdfFlow](#PdfFlow) | L'idée principale de cette conversion repose sur la sauvegarde de l'ordre "naturel" du rendu du contenu qui se forme lors du traitement des documents pdf. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Renvoie la constante d'énumération de ce type avec le nom spécifié. |
| [values](#values--) | Renvoie un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées. |

### Fixed {#Fixed}
```
public static final EpubSaveOptions.RecognitionMode Fixed
```

Ce mode est rapide et bon pour préserver au maximum l'apparence originale des pages, mais malheureusement de nombreux lecteurs EPUB ne prennent pas en charge le xhtml à mise en page fixe

### Flow {#Flow}
```
public static final EpubSaveOptions.RecognitionMode Flow
```

Mode de reconnaissance complète, le moteur tente d'effectuer le regroupement et une analyse à plusieurs niveaux pour restaurer l'intention de l'auteur du document original et produire du xhtml en mise en page fluide.

### PdfFlow {#PdfFlow}
```
public static final EpubSaveOptions.RecognitionMode PdfFlow
```

L'idée principale de cette conversion repose sur la sauvegarde de l'ordre "naturel" du rendu du contenu qui se forme lors du traitement des documents pdf.

### getByValue {#getByValue-int-}
```
public static EpubSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Renvoie la constante d'énumération de ce type avec le nom spécifié.

### values {#values--}
```
public static EpubSaveOptions.RecognitionMode [] values()
```

Renvoie un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées.

**Returns:**
un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées
