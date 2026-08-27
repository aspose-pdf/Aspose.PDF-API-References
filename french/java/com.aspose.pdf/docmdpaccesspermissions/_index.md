---
title: "DocMDPAccessPermissions"
linktitle: "DocMDPAccessPermissions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Les autorisations d'accès accordées pour ce document. Les valeurs valides sont : 1 - Aucun changement au document n'est autorisé ; toute modification du document invalide la signature. 2 -."
type: docs
weight: 1010
url: /fr/java/com.aspose.pdf/docmdpaccesspermissions/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < DocMDPAccessPermissions > com.aspose.pdf.DocMDPAccessPermissions, java.lang.Enum < DocMDPAccessPermissions >, com.aspose.pdf.DocMDPAccessPermissions

**All Implemented Interfaces:**
Serializable, Comparable < DocMDPAccessPermissions >

```
public enum DocMDPAccessPermissions extends Enum < DocMDPAccessPermissions >
```

Les autorisations d'accès accordées pour ce document. Les valeurs valides sont : 1 - Aucun changement du document n'est autorisé ; toute modification du document invalide la signature. 2 - Les changements autorisés sont le remplissage des formulaires, l'instanciation de modèles de page et la signature ; d'autres modifications invalident la signature. 3 - Les changements autorisés sont les mêmes que pour 2, ainsi que la création, la suppression et la modification d'annotations ; d'autres modifications invalident la signature.

## Champs

| Champ | Description |
| --- | --- |
| [AnnotationModification](#AnnotationModification) | 3 - Les modifications autorisées sont les mêmes que pour 2, ainsi que la création, la suppression et la modification d'annotations ; d'autres modifications invalident la signature. |
| [FillingInForms](#FillingInForms) | 2 - Les modifications autorisées sont le remplissage de formulaires, l'instanciation de modèles de page et la signature ; d'autres modifications invalident la signature. |
| [NoChanges](#NoChanges) | 1 - Aucun changement au document n'est autorisé ; toute modification du document invalide la signature. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Renvoie la constante d'énumération de ce type avec le nom spécifié. |
| [values](#values--) | Renvoie un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées. |

### AnnotationModification {#AnnotationModification}
```
public static final DocMDPAccessPermissions AnnotationModification
```

3 - Les modifications autorisées sont les mêmes que pour 2, ainsi que la création, la suppression et la modification d'annotations ; d'autres modifications invalident la signature.

### FillingInForms {#FillingInForms}
```
public static final DocMDPAccessPermissions FillingInForms
```

2 - Les modifications autorisées sont le remplissage de formulaires, l'instanciation de modèles de page et la signature ; d'autres modifications invalident la signature.

### NoChanges {#NoChanges}
```
public static final DocMDPAccessPermissions NoChanges
```

1 - Aucun changement au document n'est autorisé ; toute modification du document invalide la signature.

### getByValue {#getByValue-int-}
```
public static DocMDPAccessPermissions getByValue(int value)
```



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Renvoie la constante d'énumération de ce type avec le nom spécifié.

### values {#values--}
```
public static DocMDPAccessPermissions [] values()
```

Renvoie un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées.

**Returns:**
un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées
