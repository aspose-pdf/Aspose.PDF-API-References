---
title: "com.aspose.ms.System.MulticastDelegate>"
linktitle: "com.aspose.ms.System.MulticastDelegate>"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant des événements"
type: docs
weight: 740
url: /fr/java/com.aspose.pdf/com.aspose.ms.system.multicastdelegate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfEvent<T>

```
public abstract class PdfEvent<T extends com.aspose.ms.System.MulticastDelegate> extends Object
```

Classe représentant des événements

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfEvent](#PdfEvent--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-T-) | Ajouter un autre délégué. |
| [assign](#assign-T-) | Ajouter uniquement le délégué actuel, en supprimant les autres. |
| [clear](#clear--) | Effacer la liste des délégués |
| [isEmpty](#isEmpty--) | Renvoie vrai si la liste des gestionnaires est vide |
| [remove](#remove-T-) | Supprimer le délégué de la liste |

### PdfEvent {#PdfEvent--}
```
public PdfEvent()
```



### add {#add-T-}
```
public final void add( T delegate)
```

Ajouter un autre délégué.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| délégué |  | Objet Handlers |

### assign {#assign-T-}
```
public final void assign( T delegate)
```

Ajouter uniquement le délégué actuel, en supprimant les autres.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| délégué |  | Objet Handlers |

### clear {#clear--}
```
public final void clear()
```

Effacer la liste des délégués

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Renvoie vrai si la liste des gestionnaires est vide

**Returns:**
valeur booléenne

### remove {#remove-T-}
```
public final void remove( T delegate)
```

Supprimer le délégué de la liste

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| délégué |  | Objet Handlers |
