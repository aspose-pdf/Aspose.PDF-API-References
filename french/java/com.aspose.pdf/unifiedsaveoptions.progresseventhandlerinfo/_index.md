---
title: "UnifiedSaveOptions.ProgressEventHandlerInfo"
linktitle: "UnifiedSaveOptions.ProgressEventHandlerInfo"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Cette classe représente les informations sur la progression de la conversion qui peuvent être utilisées dans une application externe pour afficher la progression de la conversion à l'utilisateur final."
type: docs
weight: 5440
url: /fr/java/com.aspose.pdf/unifiedsaveoptions.progresseventhandlerinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.UnifiedSaveOptions.ProgressEventHandlerInfo

```
public static class UnifiedSaveOptions.ProgressEventHandlerInfo extends Object
```

Cette classe représente les informations sur la progression de la conversion qui peuvent être utilisées dans une application externe pour afficher la progression de la conversion à l'utilisateur final.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getDocumentId](#getDocumentId--) | L'ID unique du document. |
| [getEventType](#getEventType--) | Type d'événement de progression qui s'est produit |
| [getMaxValue](#getMaxValue--) | Valeur maximale possible de la progression |
| [getValue](#getValue--) | Valeur actuelle de la progression |
| [setDocumentId](#setDocumentId-com.aspose.ms.System.Guid-) | L'ID unique du document. |
| [setEventType](#setEventType-int-) | Type d'événement de progression qui s'est produit |
| [setMaxValue](#setMaxValue-int-) | Valeur maximale possible de la progression |
| [setValue](#setValue-int-) | Valeur actuelle de la progression |

### getDocumentId {#getDocumentId--}
```
public com.aspose.ms.System.Guid getDocumentId()
```

L'ID unique du document.

**Returns:**
Instance Guid

### getEventType {#getEventType--}
```
public int getEventType()
```

Type d'événement de progression qui s'est produit

**Returns:**
Élément ProgressEventType @see ProgressEventType

### getMaxValue {#getMaxValue--}
```
public int getMaxValue()
```

Valeur maximale possible de la progression

**Returns:**
valeur int

### getValue {#getValue--}
```
public int getValue()
```

Valeur actuelle de la progression

**Returns:**
valeur int

### setDocumentId {#setDocumentId-com.aspose.ms.System.Guid-}
L'ID unique du document.

### setEventType {#setEventType-int-}
```
public void setEventType(int eventType)
```

Type d'événement de progression qui s'est produit

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| eventType |  | Élément ProgressEventType @see ProgressEventType |

### setMaxValue {#setMaxValue-int-}
```
public void setMaxValue(int maxValue)
```

Valeur maximale possible de la progression

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| maxValue |  | valeur int |

### setValue {#setValue-int-}
```
public void setValue(int value)
```

Valeur actuelle de la progression

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |
