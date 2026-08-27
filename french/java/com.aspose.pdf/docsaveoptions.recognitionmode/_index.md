---
title: "DocSaveOptions.RecognitionMode"
linktitle: "DocSaveOptions.RecognitionMode"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Permet de contrôler comment un document PDF est converti en document de traitement de texte. Utilisez le mode RecognitionMode.Textbox lorsque le document résultant ne sera pas fortement."
type: docs
weight: 1050
url: /fr/java/com.aspose.pdf/docsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < DocSaveOptions.RecognitionMode > com.aspose.pdf.DocSaveOptions.RecognitionMode, java.lang.Enum < DocSaveOptions.RecognitionMode >, com.aspose.pdf.DocSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < DocSaveOptions.RecognitionMode >

```
public static enum DocSaveOptions.RecognitionMode extends Enum < DocSaveOptions.RecognitionMode >
```

Permet de contrôler comment un document PDF est converti en document de traitement de texte. Utilisez le mode RecognitionMode.Textbox lorsque le document résultant ne sera pas fortement édité par la suite. Les zones de texte sont faciles à modifier lorsqu'il n'y a pas grand-chose à faire. Utilisez le mode RecognitionMode.Flow lorsque le document de sortie nécessite une édition supplémentaire. Les paragraphes et les lignes de texte en mode flux permettent une modification facile du texte, mais les objets de formatage non pris en charge auront un rendu pire que dans le mode RecognitionMode.Textbox.

## Champs

| Champ | Description |
| --- | --- |
| [EnhancedFlow](#EnhancedFlow) | Un mode Flow alternatif qui prend en charge la reconnaissance des tableaux. |
| [Flow](#Flow) | Mode de reconnaissance complet, le moteur effectue le regroupement et une analyse à plusieurs niveaux pour restaurer l'intention de l'auteur du document original et produire un document maximablement modifiable. |
| [Textbox](#Textbox) | Ce mode est rapide et bon pour préserver au maximum l'apparence originale du fichier PDF, mais la modifiabilité du document résultant peut être limitée. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Renvoie la constante d'énumération de ce type avec le nom spécifié. |
| [values](#values--) | Renvoie un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées. |

### EnhancedFlow {#EnhancedFlow}
```
public static final DocSaveOptions.RecognitionMode EnhancedFlow
```

Un mode Flow alternatif qui prend en charge la reconnaissance des tableaux.

### Flow {#Flow}
```
public static final DocSaveOptions.RecognitionMode Flow
```

Mode de reconnaissance complet, le moteur effectue le regroupement et une analyse à plusieurs niveaux pour restaurer l'intention de l'auteur du document original et produire un document maximablement modifiable.

### Textbox {#Textbox}
```
public static final DocSaveOptions.RecognitionMode Textbox
```

Ce mode est rapide et bon pour préserver au maximum l'apparence originale du fichier PDF, mais la modifiabilité du document résultant peut être limitée.

### getByValue {#getByValue-int-}
```
public static DocSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Renvoie la constante d'énumération de ce type avec le nom spécifié.

### values {#values--}
```
public static DocSaveOptions.RecognitionMode [] values()
```

Renvoie un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées.

**Returns:**
un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées
